---
layout: default
path: /comp/index.html
title: comp
---

<a rel='me' href='http://stackoverflow.com/users/143739'>
<img src='http://stackoverflow.com/users/flair/143739.png' alt='Stack Overflow profile for kzh at Stack Overflow, Q&amp;A for professional and enthusiast programmers'/>
</a>

I am a computer science major at <a href='http://www.aug.edu/'>ASU</a> and a software developer at <a href='http://www.esi911.com/'>ESI</a>. Check out my <a href='../root/Portfolio/index.html'>portfolio</a>.

Favorites
-------------

- OS: <a href='../comp/os/linux/index.html'>GNU/Linux</a>
- Programming Language: <a rel='nofollow' href='../comp/lang/python/index.html'>Python</a>
- Data Transport Language: <a rel='nofollow' href='http://www.yaml.org/'>YAML</a>

Links
--------

- [Git vs. Mercurial](http://gitvsmercurial.com/)

Posts
---------

{% for post in site.categories.comp %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}


Subpages
--------------

<a href="databases/">databases</a>
<a href="editors/">editors</a>
<a href="lang/">lang</a>
<a href="misc/">misc</a>
<a href="org/">org</a>
<a href="os/">os</a>
<a href="programming/">programming</a>
<a href="text/">text</a>