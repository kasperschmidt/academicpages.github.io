---
layout: archive
title: "portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html reversed %}
{% endfor %}
