---
title: "News"
layout: textlay
excerpt: "VMD Lab at University of Tokyo."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }} <br>
{{ article.headline | markdownify}} <br>
{% endfor %} 
