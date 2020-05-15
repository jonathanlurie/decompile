---
layout: layouts/base.njk
pageClass: posts
templateEngineOverride: njk, md
---

<p class="date">
  <time datetime="{{ date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
</p>
<main>
  {{ content | safe }}
  <div class="footnote">
  </div>
</main>
