---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
 
Journal Papers
---
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Refereed Conference Proceedings
----
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Working Papers
----
