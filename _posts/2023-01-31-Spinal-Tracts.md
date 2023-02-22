---
layout: pdf
title: "Spinal Tracts"
date: 2023-01-31
category: "Medical"
---

<a href="/pdf/blog/spinal_tracts.pdf" download>Download</a>

<div class="image-show">
{% for image in site.static_files %}
    {% if image.path contains 'images/blog/spinal_tracts' %}
<img src="{{ site.url }}{{ image.path }}" alt="image" width="100%" style="display:block; float:left">
    {% endif %}
{% endfor %}
</div>