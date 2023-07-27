---
layout: archive
title: "Team Members"
permalink: /team/
author_profile: true
header:

---
Page is still underconstruction, pardon the formatting!
<nbsp>
  
{% include base_path %}

{% for post in site.team %}
  {% include archive-single.html type="grid" %}
{% endfor %}

