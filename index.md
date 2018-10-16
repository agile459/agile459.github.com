---
layout: page
title: Home
---

## はじめまして

Agile459は、四国地域においてアジャイルな開発、アジャイルなビジネスを実践研究するためのコミュニティです。

[アジャイルプロセス協議会](http://www.agileprocess.jp)四国支部も兼ねています。

詳しい情報は[Agile459とは](about.html)を参照ください。

## 最新の投稿

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      {{ post.date | date_to_string }}
      <a href="{{ post.url }}">
        <p>{{ post.title }}</p>
      </a>
    </li>
  {% endfor %}
</ul>

