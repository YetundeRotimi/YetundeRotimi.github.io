---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Research Gate profile</a>.</u>
{% endif %}

https://www.researchgate.net/profile/Yetunde-Rotimi

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
