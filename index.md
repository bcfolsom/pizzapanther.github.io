# this is the home page

<ul>
{% for post in site.posts %}
<li>[{{ post.title }}]({{ post.url }})</li>
{% endfor %}
</ul>
