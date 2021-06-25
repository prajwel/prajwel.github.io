---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can find my articles on <a href="https://scholar.google.co.in/citations?user=zSnUDggAAAAJ&hl=en">my Google Scholar profile</a>.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
