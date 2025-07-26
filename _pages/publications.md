---
layout: archive
permalink: /publications/
title: "Publications"
author_profile: true
---


<div class="archive-container">
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
</div>