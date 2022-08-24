---
layout: page
title: Semester Calendar
nav_order: 3
description: An embedded Google Calendar displaying the weekly event schedule.
---

# Course Calendar

{% for module in site.modules %}
{{ module }}
{% endfor %}

---
