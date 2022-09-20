---
layout: archive
title: "Publications, preprints and talks"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<p>&#42;,<sup>&#8224;</sup> denote equal contribution</p>

{% for post in site.publications reversed%}
  {% include archive-single.html %}
{% endfor %}
