---
layout: default
title: "Music"
---

One of the constants in my life is music. Enjoy some of my recordings here.

[![Me playing some viola music]](https://youtu.be/hODDlvRoJO0)

<p align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/hODDlvRoJO0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>


{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
