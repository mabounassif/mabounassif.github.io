---
layout: default
---
### Blog Posts
---
{% for category in site.categories %}
  - {{ category | first | upcase }}
    {% for post in category.last %}
    - <a href="{{ post.url }}">{{ post.title }}</a>
    {% endfor %}
{% endfor %}