---
permalink: /blogs/
title: "Blogs"
layout: archive
author_profile: true
---

Browse the latest posts below.

<div class="archive">
  {% for post in site.blogs %}
    <div class="archive__item">
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt | strip_html }}</p>
    </div>
  {% endfor %}
</div>
