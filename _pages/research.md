---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

[International Centre for Theoretical Physics Asia-Pacific](https://ictp-ap.org/)
------
Advisor: Prof. Jun Nian

[Center for Theoretical Physics, Wuhan University](http://202.114.78.174/ctp/)
------
Advisor: Prof. Junji Jia

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
