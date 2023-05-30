---
layout: post
title: Welcome  To  My Blog.
---


<h1>This is my  first github pages blog  </h1>


<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
