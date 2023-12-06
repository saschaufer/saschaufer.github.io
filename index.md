---
# Blue: 3030d1
#
permalink: /
layout: default
title: "Home"
---

# Public repositories

Here are all my public repositories. Feel free to browse through them and use them in your own projects as you wish.

{% for repository in site.github.public_repositories %}
  <blockquote>
  <a class="preview-title" href="{{ repository.html_url }}">{{ repository.name }}</a>
  <p>{{ repository.description }}</p>
  </blockquote>
{% endfor %}
