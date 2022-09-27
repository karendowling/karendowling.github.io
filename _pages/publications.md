---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign i = 0 %}

<h2>GaN Hall-effect Sensors</h2>

{% for post in site.publications reversed %}
  {% if post.category == 'Hall' %}
 {% include archive-single.html %}
 
  {% endif %}
{% endfor %}

<h2>SiC Micromachining</h2>

{% for post in site.publications reversed %}
  {%if post.category == 'SiCmachine' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Photoconductive Semiconductor Switches (PCSS)</h2>

{% for post in site.publications reversed %}
  {%if post.category == 'PCSS' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Laser Micromachining & Pressure Sensors</h2>
{% for post in site.publications reversed %}
  {%if post.category ==  'Pressure' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

{% for post in site.publications reversed %}
  {%if post.category == 'LaserCut' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>UV Photo Detectors</h2>

{% for post in site.publications reversed %}
  {%if post.category == 'UVPhoto' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Other Sensor Activities</h2>

{% for post in site.publications reversed %}
  {%if post.category == 'Thermo'%}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

{% for post in site.publications reversed %}
  {%if post.category ==  'Tactile' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


{% for post in site.publications reversed %}
  {%if post.category == 'Package'%}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
