---
layout: archive
title: "Publications and Working Papers"
permalink: /publications/
author_profile: true
---

<h1>Algorithms and Optimization</h1>

{% for post in site.publications reversed %}
  {% if post.category == "algopt"  %}
    {% include archive-pub.html %}
  {% endif %}
{% endfor %}

<h1>NLP and Economic Research</h1>

{% for post in site.publications reversed %}
  {% if post.category == "nlp" or post.category == "nlpecon"  %}
    {% include archive-pub.html %}
  {% endif %}
{% endfor %}