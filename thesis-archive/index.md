---
title: Thesis Archive
background: images/backgrounds/uofg.jpeg
redirect_from:
  - /theses
---

# <i class="fas fa-graduation-cap"></i>Thesis Archive

<p style="text-align: center;">
Doctoral dissertations at the University of Glasgow linked from the <a href="https://theses.gla.ac.uk/">Enlighten</a> repository (only Glasgow records). The list is curated from our <a href="{{ 'alumni' | relative_url }}">alumni</a> PhD roster; a few older names are not yet matched to an Enlighten entry—see the comment in the site data file.
</p>

<!-- section break -->

{% capture html %}
{% include thesis-archive-list.html %}
{% endcapture %}

{% include centerer.html html=html %}
