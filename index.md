---
layout: home
title: Welcome to My Website
---

# Welcome to My Website

This is my personal website where I share my thoughts, projects, and experiences.

## Recent Posts

{% for post in site.posts limit:3 %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## About Me

I'm passionate about technology and sharing knowledge. Feel free to [contact me](/contact) or check out my [projects](/projects).