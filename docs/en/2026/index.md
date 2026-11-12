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
        <strong>{{ lecture.date | date: '%-m/%-d' }}</strong>:
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

*   **1/12/26**: [Course Overview + Introduction to the Shell](course-shell.md)
*   **1/13/26**: [Command-line Environment](command-line-environment.md)
*   **1/14/26**: [Development Environment and Tools](development-environment.md)
*   **1/15/26**: [Debugging and Profiling](debugging-profiling.md)
*   **1/16/26**: [Version Control and Git](version-control.md)
*   **1/20/26**: [Packaging and Shipping Code](shipping-code.md)
*   **1/21/26**: [Agentic Coding](agentic-coding.md)
*   **1/22/26**: [Beyond the Code](beyond-code.md)
*   **1/23/26**: [Code Quality](code-quality.md)


Video recordings of the lectures are available [on YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQunmnnTXrNbZnBaCA-ieK4L).

## Beyond MIT

We've also shared this class beyond MIT in the hopes that others may benefit from these resources. You can find posts and discussion on

- [Hacker News](https://news.ycombinator.com/item?id=47124171)
- [Lobsters](https://lobste.rs/s/q4ykw7/missing_semester_your_cs_education_2026)
- [r/learnprogramming](https://www.reddit.com/r/learnprogramming/comments/1r93yk6/the_missing_semester_of_your_cs_education_)
- [X](https://x.com/anishathalye/status/2024521145777848588)
- [Bluesky](https://bsky.app/profile/jonhoo.eu/post/3mfa2bhyuj22i)
- [Mastodon](https://fosstodon.org/@jonhoo/116098318361854057)
- [LinkedIn](https://www.linkedin.com/posts/anishathalye_i-returned-to-mit-during-iap-january-term-activity-7430285026933522433-Ehr9)
- [YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQunmnnTXrNbZnBaCA-ieK4L)

## Acknowledgments

We thank Elaine Mello and [MIT Open Learning](https://openlearning.mit.edu/) for making it possible for us to record lecture videos. We thank Luis Turino / [SIPB](https://sipb.mit.edu/) for supporting this class as part of [SIPB IAP 2026](https://sipb.mit.edu/iap/).
