# Iterations {: style=font-family:"impact;"}

{% include navbar.html %}
{% for post in site.poems %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}