---
layout: archive
title: "Team"
permalink: /team/
author_profile: true
redirect_from:
  - /wordpress/cv/
---


{% include base_path %}

{% for post in site.team reversed %}
  {% include archive-single.html %}
{% endfor %}
