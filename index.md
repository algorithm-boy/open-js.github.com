---
layout: page
title: Hello OpenJser!
tagline: welcome here
---
{% include JB/setup %}

#### 欢迎来到 **开放JS** 门户社区，这里可以提供给你的包括

    1 详细的文档，包括标准的API以及使用方法.
    2 一些API的使用案例，详解，细节剖析 & 一些官方教程，最佳实践.
    3 常用问题与答案.
    4 一些优秀的文章, 由各位开发者提供.
    5 您的宝贵建议, 您的需求.

-------------------------------------------------

#### 最新文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
