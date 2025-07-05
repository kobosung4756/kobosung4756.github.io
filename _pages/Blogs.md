---
layout: splash        # Minimal Mistakes가 제공하는 '홈' 레이아웃
title: "Blogs"
permalink: /blogs/        # 루트 URL에 매핑
entries_layout: list
---

<div class="posts-list grid grid-cols-3 gap-6">
  {% for post in site.posts %}
    {% include archive-single.html post=post %}
  {% endfor %}
</div>
