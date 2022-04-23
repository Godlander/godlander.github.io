---
layout: default
---

<div class="home">
  <ul class="post-list">
    {% for post in site.blog %}
      <div class="post-meta">{{ post.tags | join:"&ensp;" }}</div>
      <li><h2><a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></h2></li>
    {% endfor %}
  </ul>
</div>