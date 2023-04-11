---
title: Portfolio
subtitle: Stuff I've done.
layout: gallery
---
This is a test.
<div class="gallery">
  {% for post in paginator.posts %}
  <div class="item">
    <a class="item-inner" href="{{ post.url }}">
      <div class="item-image"><img src="/thumbnails/{{ post.thumbnail }}"></div>
      <div class="item-name">{{ post.title }}</div>
    </a>
  </div>
  {% endfor %}
</div>
