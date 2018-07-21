---
layout: default
title: ブログ記事一覧
---
# {{ page.title }}
        
{% for post in site.posts %}
{% if post.lang == 'ja' %} 
{{ post.date | date_to_string }} [{{ post.title }}]({{ post.url }})
{% endif %}
{% endfor %}

[back](../)
