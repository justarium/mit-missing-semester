---
layout: page
title: "2026 Lectures"
description: >
  Lecture notes and videos for Missing Semester, MIT IAP 2026.
permalink: /
phony: true
---

<!-- <ul class="double-spaced">
  {% assign lectures = site['2026'] | sort: 'date' %}
  {% for lecture in lectures %}
    {% if lecture.phony != true %}
      <li>
        <strong>{{ lecture.date | date: '%-m/%d' }}</strong>:
        {% if lecture.ready %}
          <a href="{{ lecture.url }}">{{ lecture.title }}</a>
        {% elsif lecture.noclass %}
          {{ lecture.title }} [no class]
        {% else %}
          {{ lecture.title }} [coming soon]
        {% endif %}
        {% if lecture.details %}
          <br>
          ({{ lecture.details }})
        {% endif %}
      </li>
    {% endif %}
  {% endfor %}
</ul> -->

*   **1/12/26**: [课程概览 + Shell 入门](course-shell.md)
*   **1/13/26**: [命令行环境](command-line-environment.md)
*   **1/14/26**: [开发环境与工具](development-environment.md)
*   **1/15/26**: [Debugging and Profiling](debugging-profiling.md)
*   **1/16/26**: [Version Control and Git](version-control.md)
*   **1/20/26**: [Packaging and Shipping Code](shipping-code.md)
*   **1/21/26**: [智能体编程](agentic-coding.md)
*   **1/22/26**: [不止于代码](beyond-code.md)
*   **1/23/26**: [代码质量](code-quality.md)
