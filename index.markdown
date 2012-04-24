---
layout: default
title: Welcome
---

# This is H1

## This is H2

## This is H3

This is text

```
this is code
this is code
this is code
```

## Blog Posts

<ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

This is text

    This is indented code?
    This is indented code?
    This is indented code?
    This is indented code?

This is text