---
layout: page
title: my leggero
navigation: false
permalink: /motorcycling/leggero/
---

Who knows what went inside my head, a few years ago I decided to transform my Ducati SS900ie into a Walt Siegl Leggero. I contacted Walt who sold me a frame, tank and a bunch of parts and sent me on my way...

I had a lot of fun re-building it but it never really worked. So I had to part with it. A lot of fun, but I'll never do it again!

{% for image in site.static_files %}
    {% if image.path contains '/motorcycling/leggero/' %}
![]({{ image.path }})
    {% endif %}
{% endfor %}

