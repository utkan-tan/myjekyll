---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Welcome to my HOme Page

{% assign date = '2021-12-28T22:50:00Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}
