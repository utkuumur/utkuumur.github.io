---
layout: archive
title: "Publications and Working Papers"
permalink: /publications/
author_profile: true
---

<h1>Theoretical Computer Science and Optimization</h1>

{% for post in site.publications reversed %}
  {% if post.category == "theory"  %}
    {% include archive-pub.html %}
  {% endif %}
{% endfor %}

<h1>Natural Language Processing and Economic Research</h1>

{% for post in site.publications reversed %}
  {% if post.category == "nlp"  %}
    {% include archive-pub.html %}
  {% endif %}
{% endfor %}