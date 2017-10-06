---
layout: archive
permalink: /art/
title: "My Awesome Artwork"
image:
  feature: featured1024x256-1.png
---

<div class="tiles">
{% for post in site.categories.art %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
