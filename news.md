---
layout: page
title: News 
permalink: /news/
---

For the latest updates please check out our social media pages:

<a href="https://www.facebook.com/fgbg.uk/" target="_Blank">FGBG Facebook Page</a>

<a href="https://www.instagram.com/fgbglondon?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_Blank">FGBG Instagram</a>


{% for post in site.posts %}
### [{{post.title}}]({{post.url}})
{{ post.date | date_to_string }}
{{ post.excerpt }}

* * *
{% endfor %}

