---
layout: page
title: 📅 Schedule
nav_order: 3
description: The weekly event schedule.
---

# Schedule

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
