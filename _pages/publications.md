---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

To view the full list of my first and contributed author papers, please visit [my ADS library.](https://ui.adsabs.harvard.edu/public-libraries/r9Pm9famSwCf4HvEHMDe9g)

Please visit the Portfolio tab for updates on papers currently in prep.

First Author Publications
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
