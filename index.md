---
layout: page
title: Welcome!
tagline: (-_-).
---
{% include JB/setup %}

Blog: [54dev.com](http://www.54dev.com)
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
