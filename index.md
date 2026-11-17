---
layout: default
title: Home
hide_nav: true
hide_banner: true
---

<section class="landing-page" aria-labelledby="landing-title">
  <div class="landing-rainbow-frame" aria-hidden="true"></div>

  <header class="landing-heading">
    <p class="landing-kicker">Welcome to the small world of</p>
    <h1 id="landing-title">Grace Somin Lee</h1>
  </header>

  <svg class="landing-botanical" viewBox="0 0 420 720" aria-hidden="true">
    <path class="botanical-stem" d="M205 706c4-122 0-226 16-326 11-72 43-117 55-179 8-45 4-92-10-154"></path>
    <path class="botanical-stem" d="M219 487c-52-58-89-117-107-190-14-56-10-120 7-181"></path>
    <path class="botanical-stem" d="M221 408c45-45 79-99 96-164"></path>
    <path class="botanical-leaf" d="M177 527c-57-40-104-41-141-7 32 50 80 63 151 34Z"></path>
    <path class="botanical-leaf" d="M234 569c44-58 94-78 148-58-14 61-62 90-145 87Z"></path>
    <path class="botanical-leaf" d="M142 315c-61-23-101-9-124 36 44 33 90 29 140-14Z"></path>
    <path class="botanical-leaf" d="M265 324c43-45 87-56 132-31-20 53-63 73-128 55Z"></path>
    <path class="botanical-leaf" d="M119 148C70 102 38 50 50 3c58 2 91 44 97 126Z"></path>
    <path class="botanical-leaf" d="M270 190c21-60 57-91 108-91 8 56-22 94-99 119Z"></path>
    <path class="botanical-bloom" d="M207 276c-31-48-26-92 15-128 46 37 54 82 23 135Z"></path>
  </svg>

  <nav class="section-index" aria-label="Explore the website">
    <a class="section-index-item section-index-item--about" href="{{ '/about/' | relative_url }}">
      <span class="section-index-icon" aria-hidden="true">
        <svg viewBox="0 0 64 64">
          <circle cx="32" cy="22" r="10"></circle>
          <path d="M14 52c2.5-11 9-17 18-17s15.5 6 18 17"></path>
          <path d="M20 19c2-7 6.5-11 13-11 5.5 0 9.5 3 11.5 8"></path>
        </svg>
      </span>
      <span class="section-index-copy">
        <strong>About Me</strong>
        <small>Who I am and what moves me</small>
      </span>
    </a>

    <a class="section-index-item section-index-item--projects" href="{{ '/projects/' | relative_url }}">
      <span class="section-index-icon" aria-hidden="true">
        <svg viewBox="0 0 64 64">
          <path d="M13 18h15l5 6h18v28H13z"></path>
          <path d="M20 34h24M20 42h18"></path>
          <path d="M43 12l2 5 5 2-5 2-2 5-2-5-5-2 5-2z"></path>
        </svg>
      </span>
      <span class="section-index-copy">
        <strong>Projects</strong>
        <small>Research, writing, and works in progress</small>
      </span>
    </a>

    <a class="section-index-item section-index-item--beings" href="{{ '/beings/' | relative_url }}">
      <span class="section-index-icon" aria-hidden="true">
        <svg viewBox="0 0 64 64">
          <path d="M32 32C25 15 12 14 10 25c-1 8 8 13 22 7Z"></path>
          <path d="M32 32c7-17 20-18 22-7 1 8-8 13-22 7Z"></path>
          <path d="M32 32c-7 17-20 18-22 7-1-8 8-13 22-7Z"></path>
          <path d="M32 32c7 17 20 18 22 7 1-8-8-13-22-7Z"></path>
          <path d="M32 17v30"></path>
        </svg>
      </span>
      <span class="section-index-copy">
        <strong>Beings</strong>
        <small>Stories of those who shape my creations</small>
      </span>
    </a>
  </nav>

  <p class="landing-note">Choose a circle to enter</p>
</section>
