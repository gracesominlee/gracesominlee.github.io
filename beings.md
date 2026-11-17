---
layout: default
title: Beings
permalink: /beings/
---

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
