---
layout: page
title: Summaries
permalink: /summary/
---

You can search for something specific on the home page, but if you need a specific
item then you'll find it here.

I'm not intimately familiar with how the NGC originally categorized its information,
so if you have better ideas then please feel free to let me know.

<ul>
    {% for s in site.summary %}
    <li><a href="{{ s.url }}">{{ s.title | default: s.id }}</a></li>
    {% endfor %}
</ul>