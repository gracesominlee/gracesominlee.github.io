---
layout: default
title: Beings
permalink: /beings/
nav_key: beings
---

<section class="beings-network" aria-label="Interactive floating network of beings that have contributed to my creations">
  <p class="beings-intro">Click a being to pause it and read its story.</p>
  <div class="beings-stage" data-beings-stage></div>
</section>

<script type="application/json" id="beings-data">
  {{ site.data.beings | jsonify }}
</script>
<script src="{{ '/assets/js/beings-network.js' | relative_url }}"></script>
