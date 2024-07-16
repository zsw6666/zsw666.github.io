---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my papers on [ADS Library](https://ui.adsabs.harvard.edu/search/filter_author_facet_hier_fq_author=AND&filter_author_facet_hier_fq_author=author_facet_hier%3A%221%2FZhang%2C%20S%2FZhang%2C%20Shiwu%22&filter_database_fq_database=AND&filter_database_fq_database=((database%3Aastronomy%20OR%20database%3Aphysics))&filter_database_fq_database=database%3A%22astronomy%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq=%7B!type%3Daqp%20v%3D%24fq_author%7D&fq_author=(author_facet_hier%3A%221%2FZhang%2C%20S%2FZhang%2C%20Shiwu%22)&fq_database=(((database%3Aastronomy%20OR%20database%3Aphysics))%20AND%20database%3A%22astronomy%22)&q=%20author%3A%22Zhang%2C%20Shiwu%22%20year%3A2018-2024&sort=date%20desc%2C%20bibcode%20desc&p_=0)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
