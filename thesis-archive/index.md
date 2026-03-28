---
title: Thesis Archive
background: images/backgrounds/uofg.jpeg
redirect_from:
  - /theses
---

# <i class="fas fa-graduation-cap"></i>Thesis Archive

<p style="text-align: center;">
Doctoral dissertations linked from the <a href="https://theses.gla.ac.uk/">Enlighten</a> and <a href="https://eprints.gla.ac.uk/">Glasgow ePrints</a> repositories. The list is curated from our <a href="{{ 'alumni' | relative_url }}">alumni</a> PhD roster.
</p>

<!-- section break -->

{% capture html %}
{% include thesis-archive-list.html %}
{% endcapture %}

{% include centerer.html html=html %}
