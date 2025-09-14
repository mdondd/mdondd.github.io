---
layout: page
title: Blog Archive
permalink: /archive/
---

{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}