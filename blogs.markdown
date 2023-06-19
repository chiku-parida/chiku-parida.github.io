---
layout: page
title: Blogs
permalink: /blogs/

---
### My blog posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y %b %d" }}: {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
