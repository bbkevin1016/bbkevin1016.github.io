---
layout: home
title: "欢迎光临"
description: "这是我的个人小站"
---

# 你好，我是 Kevin 👋

欢迎来到我的个人空间！

## 关于我

- 💼 软件开发者
- 🌱 目前正在学习前端技术
- 📝 偶尔写写技术博客
- 🎯 2024目标：打造个人品牌

## 最新文章

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## 联系我

- 📧 Email: your-email@example.com
- 🐙 GitHub: [@bbkevin](https://github.com/bbkevin)
