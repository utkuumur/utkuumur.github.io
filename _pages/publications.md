---
layout: archive
title: "Publications and Working Papers"
permalink: /publications/
author_profile: true
---

Theoretical Computer Science and Optimization
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
{% include base_path %}

Natural Language Processing and Textual Analytics
---

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}