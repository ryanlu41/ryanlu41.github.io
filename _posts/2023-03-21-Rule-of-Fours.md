---
layout: pdf
title: "Rule of Fours"
date: 2023-03-21
category: "Medical"
---

<a href="/pdf/blog/rule_of_fours.pdf" download>Download</a>

<div class="image-show">
{% for image in site.static_files %}
    {% if image.path contains 'images/blog/rule_of_fours' %}
<img src="{{ site.url }}{{ image.path }}" alt="image" width="100%" style="display:block; float:left">
    {% endif %}
{% endfor %}
</div>

