---
layout: page
title: Summaries
permalink: /summary/
---

You can broadly search for summaries on the [home page]({{ site.baseurl }}),
but you can find specific items here.

I don't know how the NGC originally categorized its information, so if you
have a better idea than a flat list then please let me know.

<ul>
    {% for s in site.summary %}
    <li><a href="{{ s.url | relative_url }}">{{ s.title | default: s.id }}</a></li>
    {% endfor %}
</ul>