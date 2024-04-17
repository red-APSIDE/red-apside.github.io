---
title: "News"
layout: textlay
excerpt: "Red APPSIDE."
sitemap: false
permalink: /allnews.html
---

# News
{% for article in site.data.news %}
<!-- <p>{{ article.date }} <br> {{ article.headline | markdownify}}</p> -->
<p>{{ article.date }} <br> {{ article.headline }}</p>
{% endfor %}
