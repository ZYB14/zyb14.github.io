---
layout: page
title: About
description: 关于界面
keywords: ZYB14
comments: true
menu: 关于
permalink: /about/
---

你好，这里是ZYB14，14岁，是学生。

How lucky to meet you!

## 联系

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'zyb14.netlify.app' %}
<li>
<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ site.url }}/assets/images/qrcode.jpg" alt="ZYB14" />
</li>
{% endif %}
</ul>

