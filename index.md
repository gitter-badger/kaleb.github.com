---
layout: default
title: Root
---

{% for post in site.posts limit:5 %}
<article>

# <a href="{{ post.url }}">{{ post.title }}</a>

{{ post.content }}

<em>Posted on {{ post.date | date_to_long_string }}.</em>

{{ post.categories }}
</article>
{% endfor %}
