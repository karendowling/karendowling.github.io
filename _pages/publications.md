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
