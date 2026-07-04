---
layout: page
title: Archive
permalink: /archive/
---

<h3>2026</h3>
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">
      {{ post.title }}
    </a>
  </li>
{% endfor %}
</ul>
</section>
