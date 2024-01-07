---
layout: inner
title: Personal Patterns
permalink: /personal_patterns/
---

# Personal Patterns

There are a lot of times that I want to write up knitting patterns only for myself. I don't want to publish them properly, but I do want to be able to find them again. This is a place for me to do that.

You're welcome to use them, but they're not graded, tested, and I'm not going to be providing support for them.

<ul>
{% for post in site.posts %}
    {% if post.tags contains "personal_patterns" %}
        <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endif %}
{% endfor %}
</ul>