---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.
{% endif %}

{% include base_path %}

Blog posts
-----
<h3 class="archive__item-title" itemprop="headline" style="margin-bottom:0px;">
    <a href="https://lis.csail.mit.edu/embodied-lifelong-learning-for-decision-making/">Embodied Lifelong Learning for Decision Making: Opportunities Brought on by Modularity</a>
</h3>
<p style="margin-top:0px;">
  2023
</p>


<!-- Preprints
-----

{% for post in site.publications reversed %}
  {% if post.type == 'preprint' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %} -->

Journal Articles
-----

{% for post in site.publications reversed %}
  {% if post.type == 'journal' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}

Conference Papers
-----

{% for post in site.publications reversed %}
  {% if post.type == 'conference' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}

Workshop Papers
-----

{% for post in site.publications reversed %}
  {% if post.type == 'workshop' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}


Theses
-----

{% for post in site.publications reversed %}
  {% if post.type == 'thesis' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
