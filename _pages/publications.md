---
layout: archive
title: "PublicationsXX"
permalink: /publications/
author_profile: true
---
hello

b'- Christensen, Heidi and Barker, Jon and Ma, Ning and Green, Phil D *The CHiME corpus: a resource and a challenge for computational hearing in multisource environments* (2010), Eleventh Annual Conference of the International Speech Communication Association   [bib](bib/christensen2010chime.bib)\n'b'- Christensen, Heidi and Gotoh, Yoshihiko and Renals, Steve *Punctuation annotation using statistical prosody models.* (2001)   [bib](bib/christensen2001punctuation.bib)\n'

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
