---
layout: home
title: 首页
---

这是我的 GitHub Pages，用来展示我在学习 GitHub、工程实践和 AI 应用开发过程中的成长记录。

---

## 学习日志

<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

---

## 项目

-骁龙 汇息 （开发中）

---

## 关于

深圳大学计算机专业本科生  
方向：AI 应用工程 / AI 产品工程

GitHub：
https://github.com/liguanlin1212

GitHub Pages:
https://liguanlin1212.github.io/developer-pages/
