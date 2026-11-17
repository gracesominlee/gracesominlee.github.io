---
layout: default
title: Beings
permalink: /beings/
hide_nav: true
hide_banner: true
---

<header class="interior-header">
  <div>
    <p class="interior-kicker">Grace Somin Lee</p>
    <h1>Beings</h1>
  </div>
  <a href="{{ '/' | relative_url }}" class="home-link" aria-label="Return to the home page">
    <svg viewBox="0 0 48 48" aria-hidden="true">
      <path d="M7 23.5 24 8l17 15.5"></path>
      <path d="M12 21v19h24V21M20 40V28h8v12"></path>
    </svg>
  </a>
</header>

<section class="beings-intro">
  <p>
    A floating network of all beings that have contributed to my creations. Click on them to see their stories. 
  </p>
</section>

<section class="beings-network" aria-label="Interactive beings network">
  <div class="beings-stage" data-beings-stage></div>
</section>

<script type="application/json" id="beings-data">
  {{ site.data.beings | jsonify }}
</script>
<script src="{{ '/assets/js/beings-network.js' | relative_url }}"></script>
