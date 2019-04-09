---
layout: page
title: News 
permalink: /news/
---

{% for post in site.posts %}
### [{{post.title}}]({{post.url}})
{{ post.date | date_to_string }}
{{ post.excerpt }}

* * *
{% endfor %}
