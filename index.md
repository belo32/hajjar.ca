---
layout: page
title: Bilal Al-Hajjar's Personal Page
tagline: Think simple
---
{% include JB/setup %}
Welcome to my personal page which I am currently hosting on github pages using Jekyl bootstrap.

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




