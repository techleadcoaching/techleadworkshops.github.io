---
layout: default
---

### Blog

{% for post in site.categories["blog"]  %}
  **[{{ post.title }}]({{ post.url }})** - {{post.excerpt  | remove: '<p>' | remove: '</p>'}}
{% endfor %}
