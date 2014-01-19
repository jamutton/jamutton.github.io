---
layout: page
title: Took things apart as a child
---
{% include JB/setup %}

So I haven't messed much with this yet, just getting started publishing stuff

## Posts

So the whole point of this is to have somewhere easy to dump interesting things that
doesn't require writing a bunch of HTML or entries in a rich-text editor.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

... well, post some content really.  At some point I'll get my Distributed CouchDB benchmarking stuff up.
Or just write a bit about things.

