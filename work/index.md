---
layout: archive
main: true
title: Work
subtitle: 지금까지 작업한 프로젝트
author_profile: true
---

{% assign posts = site.categories.work | sort:"order" | reverse %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}