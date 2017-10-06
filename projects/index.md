---
layout: archive
permalink: /projects/
title: "My Awesome Projects"
image:
  feature: featured1024x256-1.png
---

<div class="tiles">
{% for post in site.categories.projects %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
