---
layout: page
title: Welcome!
tagline: Won't stop, can't stop!
---
{% include JB/setup %}

### Projects
* [angularjs-table-charts-cross-filtering]({{ BASE_PATH }}/angularjs-table-charts-cross-filtering)

### Posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



