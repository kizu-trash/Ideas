---
layout: default
---

# Shared Ideas

Ok, until I would add some style, consider those ideas _naked_ :)

Here would be a list of them:

{% for post in site.posts %}
- [{{ post.title }}]({{ site.url }}{{ post.url }})
{% endfor %}

And here is a Site Url: {{ site.url }}