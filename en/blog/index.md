---
layout: default
title: Blog List
---
# {{ page.title }}
        
{% for post in site.posts %}
{% if post.lang == 'en' %} 
{{ post.date | date_to_string }} [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}

[back](../)
