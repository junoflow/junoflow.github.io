---
layout: archive
main: true
title: Work
subtitle: 지금까지 작업한 프로젝트
author_profile: true
permalink: /work/

---


{% assign posts = site.categories.work | sort:"order" | reversed %}

{% for post in posts %}
  {% include post-list.html %}
{% endfor %}