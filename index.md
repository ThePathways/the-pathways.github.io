---
layout: default
title: Home
---

# Welcome to My Jekyll Site

This is my first Jekyll site hosted on GitHub Pages!

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
