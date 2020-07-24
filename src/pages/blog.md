---
pageTitle: Blog
---

{% for post in collections.posts %}

<h2><a href="{{ post.url }}">{{ post.data.pageTitle }}</a></h2>
<em>{{ post.date | date: "%d-%m-%Y" }}</em>
{% endfor %}
