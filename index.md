---
layout: default
---
<i class="fa fa-pencil"></i> Blog
{% for post in site.posts %}
 <a href="{{ post.url |prepend: site.baseurl }}">{{ post.title }}</a>

  {% endfor %}