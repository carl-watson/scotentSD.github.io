---
layout: page
title: Blog
permalink: /blog-post-list/
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
<br><br>
<div>Last updated: {{site.time | date_to_string}}</div>


