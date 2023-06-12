---
layout: page
title: Blog
permalink: /blog/
---

### My blog posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y %b %d" }}: {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>