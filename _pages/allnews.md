---
title: "News"
layout: textlay
excerpt: "iSMART Lab"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }}
<p>{{ article.headline | markdownify}}</p>
{% endfor %}
