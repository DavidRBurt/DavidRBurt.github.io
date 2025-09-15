---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Selected publications. You can find a complete list of my publications on [my Google Scholar profile](https://scholar.google.com/citations?hl=en&user=Kve55S4AAAAJ&view_op=list_works&sortby=pubdate)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
