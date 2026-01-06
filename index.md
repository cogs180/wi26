---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
seo:
  type: Course
  name: Decision Making
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% assign instructors = site.staffers | where: 'role', 'Instructor' %} {% for staffer in instructors %} {{ staffer}} {% endfor %}

## Office Hours
* **Prof. Lai** : Tues, 2-3pm (<a href="https://calendar.app.google/1nebbtvdYdn6WFpw5" target="_blank" rel="noopener">book &#x2197;</a> only) @ CSB 244/Zoom OR Thurs, 2-3pm (walk-in) @ CSB 244
* **Sujin**: During discussion section
* **Gaby**: Monday, 12-1p @ [Zoom](https://ucsd.zoom.us/j/94515273329)
* **Sharon**: Monday, 2-3p @ [Zoom](https://ucsd.zoom.us/j/98342142527)


## Course Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
