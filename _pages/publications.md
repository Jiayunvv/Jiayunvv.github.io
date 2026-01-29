---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

You can also find my articles on my [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=Gh1-y3cAAAAJ).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
