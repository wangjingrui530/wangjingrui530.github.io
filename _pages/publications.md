---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**You can also find my articles on [my Google Scholar page](https://scholar.google.com/citations?hl=zh-CN&user=oiu-yTYAAAAJ&view_op=list_works&sortby=pubdate)**.

{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
