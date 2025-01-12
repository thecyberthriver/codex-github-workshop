---
layout: page
title: Cybersecurity Conferences
permalink: /conferences/
---

## Cybersecurity Conferences
Discover upcoming conferences designed to foster networking and knowledge sharing.

{% for conference in site.data.conferences %}
- **{{ conference.name }}**  
  Location: {{ conference.location }}  
  Dates: {{ conference.dates }}  
  Website: [{{ conference.website }}]({{ conference.website }})
{% endfor %}
