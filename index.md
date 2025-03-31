---
layout: default
title: "Blog của Mai"
---

<h1>Danh sách bài viết</h1>

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: "%B %d, %Y" }})
  </li>
{% endfor %}
</ul>
