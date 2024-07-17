---
title: "spring"
layout: single
permalink: /devRecord/
---
{% assign posts = site.categories.devRecord %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}