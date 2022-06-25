---
layout: default
title: MUSIC Lab at SUSTech
published: true
---

### Blog



<ul>
  {% for post in site.blog reversed %}
    <li>
    [{{ post.date | date_to_string }}] » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
