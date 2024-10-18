---
layout: archive
title: "Publications/Replication packages"
permalink: /publications/
author_profile: true
---


# List of publications
<div class="wordwrap">Link to <a href="https://stephandoc.github.io/files/lop.pdf">list of publications</a>.</div>


# Google scholar
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
