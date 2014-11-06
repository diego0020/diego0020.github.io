---
layout: page
title: Diego0020 Blog
tagline: Supporting tagline
---
{% include JB/setup %}

Coming soon
    
## Recent Posts

<ul class="posts">
  {% for post in site.posts limit:5%}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


