---
title: "Notícias"
layout: textlay
excerpt: "stoloca na UFBA."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
