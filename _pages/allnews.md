---
title: "Noticias"
layout: textlay
excerpt: "Red APPSIDE."
sitemap: false
permalink: /allnews.html
---

# Noticias

{% for article in site.data.news %}
<!-- <p>{{ article.date }} <br> {{ article.headline | markdownify}}</p> -->
<p>{{ article.date }} <br> {{ article.headline }}</p>
{% endfor %}
