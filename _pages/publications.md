---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

To get the full list, you could also find my publications from the below approaches:
For astronomers: [Harvard ADS](https://ui.adsabs.harvard.edu/search/q=orcid%3A0009-0000-7431-7885&sort=date+desc)
For high energy physicsists: [INSPIRE HEP](https://inspirehep.net/authors/2685932)
Generally, [Google Scholar](https://scholar.google.com/citations?user=hxR2VSsAAAAJ&hl=zh-CN&authuser=2) and [ORCID](https://orcid.org/0009-0000-7431-7885) are also available.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}