---
layout: page
title: Events 
permalink: /events/
---
{% for event in site.data.events %}
### {{ event.name }}
_{{ event.date }}_

{{ event.location }}

{{ event.description }}

* * *
{% endfor %}
