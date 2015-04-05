---
layout: page
title: Wait, who are you? Who am I?
---
{% include JB/setup %}

Hey there, so this is where most of my ramblings are going to probably live. I have the attention span of a 2 year old, the imagination of a 5 year old, the fashion sense of a 16 year old, and I have been told that I have an old soul. So who knows where this is going to end up, but I am sure it is either going to be extremely boring or really confusing. My money is on the latter.

### Post List
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>