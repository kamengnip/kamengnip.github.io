---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="https://scholar.google.com/citations?user=f9KXxU0AAAAJ">my Google Scholar profile</a>.
 
Journal Papers
------
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Refereed Conference Proceedings
------
{% for post in site.publicationscon reversed %}
  {% include archive-single.html %}
{% endfor %}

Working Papers
------
{% for post in site.publicationswork reversed %}
  {% include archive-single.html %}
{% endfor %}
