---
layout: default
title: Events
---

{% for page in site.posts %}{% if page.categories contains 'events' %}
* [{{ page.title }}]({{ page.url }})
{% endif %}{% endfor %}
