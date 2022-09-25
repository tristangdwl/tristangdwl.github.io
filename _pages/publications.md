---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

The Laplace-Beltrami problem on non-smooth surfaces
------

An integral equation method for elliptic surface PDEs
------

Publications
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



