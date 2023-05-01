---
layout: page
title: Home
id: home
permalink: /
---
# 시험 문제 다시보기
[[고1 2차고사 대비 기출모음]] &nbsp;&nbsp; [[고2 2차고사 대비 기출 모음]]



<strong>최근 업데이트된 노트</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 3 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
