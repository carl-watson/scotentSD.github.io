---
layout: page
title: Blog
permalink: /blog-post-list/
---


  {% for post in site.posts %}
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <div class="date">	
            Written on {{ post.date | date_to_string }} {% if post.author %} by {{post.author}} {% endif %}          	
       </div>	
      {{ post.excerpt }}
  {% endfor %}

<br><br>
<div>Last updated: {{site.time | date_to_string}}</div>


