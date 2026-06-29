---
layout: page
title: Course Schedule
nav_order: 1
description: Weekly lectures and assignments.
---

# Course Schedule

**Please note:** This Summer 2026 schedule is tentative. The [syllabus]({{ site.baseurl }}/src/ph142-syllabus-su26.pdf) is the authoritative reference for grading categories and due-date policies.

Lectures meet Monday through Friday, 9:30 to 10:59 AM Pacific. Live Zoom lectures are held every other day; lecture recordings are posted daily.

Labs are synchronous online Monday through Thursday, either 11:00–11:59 AM or 5:00–5:59 PM Pacific depending on section. Each day's lab questions are released that day and are due by the end of that same day.

Weekly assignments are released at the end of each week on Gradescope and are due before the next weekly assignment is released. See Ed Discussion for platform announcements.


{% for module in site.modules %}
{{ module }}
{% endfor %}
