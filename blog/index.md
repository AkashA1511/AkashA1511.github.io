---
layout: default
title: Blog
permalink: /blog/
---

# Posts

{% raw %}{% for post in site.posts %}{% endraw %}
<p>
{{ post.date | date: "%b %d, %Y" }} <br>
<a href="{{ post.url }}">{{ post.title }}</a>
</p>
{% raw %}{% endfor %}{% endraw %}
