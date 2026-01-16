---
title: "Diary"
layout: archive
permalink: /categories/diary/
author_profile: true
sidebar:
  nav: "main"
---

{% assign posts = site.categories.Diary %}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}