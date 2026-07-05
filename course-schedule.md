---
layout: page
title: Course Schedule
nav_order: 1
description: Weekly lectures and assignments.
---

# Course Schedule

**Please note:** This Summer 2026 schedule is tentative. The [syllabus]({{ site.baseurl }}/src/ph142-syllabus-su26.pdf) is the authoritative reference for grading categories and due-date policies.

{% for module in site.modules %}
{{ module }}
{% endfor %}
