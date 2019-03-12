---
layout: page
show_meta: false
title: "Kora News"
header:
   image_fullwidth: "korabridge.jpg"
permalink: "/koranews/"
---
<ul>
    {% for post in site.categories.koranews %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
