---
layout: archive
title: "PublicationsXX"
permalink: /publications/
author_profile: true
---
hello2

{% include_relative publications_list.md %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
