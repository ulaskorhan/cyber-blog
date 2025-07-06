---
title: "Archive"
layout: single
permalink: /archive/
author_profile: true
---

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) <small>({{ post.date | date: "%B %d, %Y" }})</small>
{% endfor %}
