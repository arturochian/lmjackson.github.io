---
layout: default
root: ""
---
<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% if post.title %}<h2>{{ post.title }}</h2>{% endif %}
  {{ post.content }}
</div>