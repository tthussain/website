---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Hello
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Hello2

{% include sit.publications.publications_list.md}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
