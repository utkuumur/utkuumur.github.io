---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---


<h1>Working Papers</h1>

{% for post in site.publications reversed %}
  {% if post.working == 1 %}
    {% include archive-pub.html %}
  {% endif %}
{% endfor %}

<h1>Algorithms and Optimization</h1>

{% for post in site.publications reversed %}
  {% if post.category == "algopt" and post.working != 1 %}
    {% include archive-pub.html %}
  {% endif %}
{% endfor %}

<h1>NLP and Economic Research</h1>

{% for post in site.publications reversed %}
  {% if post.category == "nlp" or post.category == "nlpecon" and post.working != 1 %}
    {% include archive-pub.html %}
  {% endif %}
{% endfor %}