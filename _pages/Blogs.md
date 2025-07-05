---
layout: archive       
title: "Blogs"
permalink: /blogs/
classes: wide
pagination:
  enabled: true 
---

<div class="posts-list grid grid-cols-3 gap-6">
  {% for post in site.posts %}
    {% include archive-single.html post=post %}
  {% endfor %}
</div>
