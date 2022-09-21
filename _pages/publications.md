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

<h3>GaN Hall-effect Sensors</h3>

{% for post in site.publications reversed %}
  {% if post.category == 'Hall' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h3>SiC Micromachining</h3>

{% for post in site.publications reversed %}
  {%if post.category == 'SiCmachine' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
