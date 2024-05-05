
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{https://scholar.google.com/citations?hl=zh-CN&user=PLujFT4AAAAJ&view_op=list_works&sortby=pubdate}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

