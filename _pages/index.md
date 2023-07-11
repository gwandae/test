---
layout: page
title: Home
id: home
permalink: /
---
# 시험 문제 다시보기
[[고1 1차고사 대비 기출모음|고1 1차고사]] &nbsp;&nbsp; [[고2 1차고사 대비 기출모음|고2 1차고사]]

[[고1 2차고사 대비 기출모음|고1 2차고사]] &nbsp;&nbsp; [[고2 2차고사 대비 기출모음|고2 2차고사]]

[[고1 3차고사 대비 기출모음|고1 3차고사]] &nbsp;&nbsp; [[고2 3차고사 대비 기출모음|고2 3차고사]]

[[고1 4차고사 대비 기출모음|고1 4차고사]] &nbsp;&nbsp; [[고2 4차고사 대비 기출모음|고2 4차고사]]

[[확통 1차고사 대비 기출모음|확통 1차고사]]  &nbsp;&nbsp; [[미적 1차고사 대비 기출모음|미적 1차고사]]

[[확통 2차고사 대비 기출모음|확통 2차고사]] &nbsp;&nbsp; [[미적 2차고사 대비 기출모음|미적 2차고사]]

[[기하 1차고사 대비 기출모음|기하 1차고사]] &nbsp;&nbsp; [[기하 2차고사 대비 기출모음|기하 2차고사]]

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
