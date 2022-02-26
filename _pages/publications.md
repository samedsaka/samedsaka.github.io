---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


  You can find my publications on <u><a href="https://scholar.google.com.tr/citations?user=avLR65QAAAAJ">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
