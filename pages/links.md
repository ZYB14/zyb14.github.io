---
layout: page
title: Links
description: 没有链接的博客是孤独的
keywords: 友情链接
comments: true
menu: 链接
permalink: /links/
---

> God made relatives. Thank God we can choose our friends.

<ul>
{% for link in site.data.links %}
  {% if link.src == 'life' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>

> 本站状态监测

[![Netlify Status](https://api.netlify.com/api/v1/badges/f1c60ea7-2b5c-45c5-9ed1-fbbade5e6ff3/deploy-status)](https://app.netlify.com/sites/zyb14/deploys)
