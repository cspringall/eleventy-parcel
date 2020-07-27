---
pageTitle: Blog
---

<!-- make new page layout -->

<!-- move to partial -->

<ul>
{% for post in collections.posts %}
<li>
    <h3><a href="{{ post.url }}">{{ post.data.pageTitle }}</a></h3>
    <p>{{ post.date | date: "%d-%m-%Y" }}</p>
</li>
{% endfor %}
</ul>
