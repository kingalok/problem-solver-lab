---
layout: default
title: Home
---
<section class="hero">
  <p class="label">Engineering Blog</p>
  <h1>Problem Solver Lab</h1>
  <p>Clear writing on AI delivery maturity, platform controls, and practical engineering systems.</p>
  <p class="hero-links">
    <a class="button" href="{{ site.posts.first.url | relative_url }}">Read latest post</a>
    <a class="button ghost" href="https://www.linkedin.com/in/kingalok-sharma/" target="_blank" rel="noopener">LinkedIn</a>
  </p>
</section>

<section class="section-head">
  <h2>Latest Articles</h2>
</section>

<section class="post-list">
  {% for post in site.posts %}
  <article class="post-card">
    <p class="meta">{{ post.date | date: "%B %d, %Y" }}</p>
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt | strip_html | truncate: 200 }}</p>
    <a class="read-more" href="{{ post.url | relative_url }}">Read article</a>
  </article>
  {% endfor %}
</section>
