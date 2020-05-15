---
title: Decompile
subtitle: Hi, I am Jonathan Lurie. </br>I write code and and I learn new things in the process. Now let's share!
layout: layouts/base.njk
---



<div class="listing">
{%- for page in collections.post -%}
  <div class="post">
    <div class="cover" style="background: url({{page.data.cover}}) no-repeat   center center; background-size: cover;" onclick="window.location = '{{ page.url }}';">
      <div class="post-container">
        <a class="post-link" href="{{ page.url }}">{{ page.data.title }}</a>
        <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
        <p>{{page.data.excerpt}}</p>
      </div>
    </div>
  </div>
{%- endfor -%}
</div>

