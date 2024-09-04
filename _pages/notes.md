---
layout: page
title: Lecture Notes
permalink: "/notes"
---

<section class="posts archive">
<ul>
{% for post in site.notes %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y-%m-%d" }}</time></li>
{% endfor %}
</ul>
</section>