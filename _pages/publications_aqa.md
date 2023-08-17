---
layout: archive
title: "Air Quality Report"
permalink: /publications_aqa/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications_aqa reversed %}
  {% include archive-single.html %}
{% endfor %}
