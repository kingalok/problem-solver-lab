---
layout: default
title: Home
---
<section class="hero">
  <p class="label">Engineering Blog</p>
  <h1>Problem Solver Lab</h1>
  <p>Notes on AI delivery maturity, agent workflows, platform guardrails, and practical systems engineering.</p>
</section>

<section class="post-grid">
  {% for post in site.posts %}
  <article class="post-card">
    <p class="meta">{{ post.date | date: "%B %d, %Y" }}</p>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p class="excerpt">{{ post.excerpt | strip_html | truncate: 180 }}</p>
  </article>
  {% endfor %}
</section>
