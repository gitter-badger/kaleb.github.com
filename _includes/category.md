{% if posts %}
Posts
---------

{% for post in posts %}
- [{{ post.title }}]({{ post.url }}){% endfor %}
{% endif %}
{% if page.subpages %}
Subpages
--------------

<nav><ol>
{% for subpage in page.subpages%}
<li>[{{subpage}}]({{subpage}}){% endfor %}
{% endif %}
</ol></nav>
