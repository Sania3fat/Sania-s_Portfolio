This portfolio showcases my projects that I did as part of Master's program in Business Analytics, and also those I did as part of my role as Data Analyst / Intern.
---
layout: default
title: Home
---

<div class="container">
  <h1>My GitHub Projects</h1>
  <ul>
    {% for post in site.posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
