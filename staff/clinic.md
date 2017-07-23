---
layout: page
title: Clinic Staff
---

{% for staff in site.staff %}
  <h2>{{ staff.name }}</h2>
  ![{{staff.name}}](/staff/{{staff.image}})
  {{ staff.content }}
  **Insurance plans accepted**: {{ staff.accepted_insurance }}
{% endfor %}
