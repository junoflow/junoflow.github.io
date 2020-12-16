---
layout: archive
main: true
title: Project
subtitle: 지금까지 수행한 대외활동과 프로젝트
author_profile: false
permalink: /project/

---


{% assign posts = site.categories.project | sort:"date" | reverse %}

{% for post in posts %}
  {% include post-list.html %}
{% endfor %}