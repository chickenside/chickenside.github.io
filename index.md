---
layout: page
title: stirringcopy.io
tagline: Words to loath for the greater good
---
{% include JB/setup %}

## A few words

Now is the time for all good men to come to the `aid` of their party.

	Now:	is the time
	For:	all good men
	To:	come to the aid
	Of:	their party

	That's some formated text.

## Posts


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

