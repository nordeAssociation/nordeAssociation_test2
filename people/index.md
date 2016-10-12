---
layout: archive
title: "Members"
date: 2016-10-10T11:39:03-04:00
modified:
#excerpt: ""
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.people %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->