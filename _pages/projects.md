---
layout: archive
permalink: projects/
title: "Projects"
header:
  overlay_image: /assets/images/code.jpg
  overlay_filter: rgba(0, 0, 0, 0.25)

last_modified_at: 2018-01-10T11:22:24-05:00
---

<div>
{% for post in site.categories.Projects %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

