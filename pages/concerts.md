---
layout: page
show_meta: false
title: "News of concert dates, festivals and tours"
header:
   image_fullwidth: "BallakeSissokoKora.jpg"
permalink: "/concerts/"
---
<ul>
    {% for post in site.categories.concerts %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
