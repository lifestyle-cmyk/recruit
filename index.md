---
layout: default
title: "ホーム"
---

# ライフスタイル情報ブログへようこそ
最新の記事はこちら👇

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
