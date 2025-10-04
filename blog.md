---
title: Blog
layout: default
permalink: /blog/
---

## My Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <h3>
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      </h3>
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
