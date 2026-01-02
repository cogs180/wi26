---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
seo:
  type: Course
  name: Modeling and Data Analysis
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% assign instructors = site.staffers | where: 'role', 'Instructor' %} {% for staffer in instructors %} {{ staffer}} {% endfor %}

## Important Course Info

|--|-----|
| **TA**         | [Jiesen Zhang](mailto:jiz147@ucsd.edu)|
| **PLAs**       | [Parinita Saha](mailto:psaha@ucsd.edu) & [Johny Nguyen](mailto:jon009@ucsd.edu)|
| **Reader**     | [Zhicheng Wang](mailto:zhw049@ucsd.edu)  |
| **Lectures**   | MWF, 9-9:50am @ CENTR 113 |
| **Discussion**   |• W, 2-2:50pm @ WLH 2113 <br> • F, 4-4:50pm @ WLH 2207 <br> • F, 5-5:50pm @ WLH 2207 |

## Office Hours

|--|-----|
| **Prof. Lai** | **• W, 2:30-3:30** (walk-in), **3:30-4pm** ([book](https://calendar.app.google/1nebbtvdYdn6WFpw5) only) @ CSB 244/Zoom <br> **• Th, 4:30-5:30pm** ([book](https://calendar.app.google/1nebbtvdYdn6WFpw5) only) on Zoom |
| **Jiesen Zhang** | During **all discussion sections** ([book](https://calendar.app.google/JRGBzv2Bc77dxiAP8) for week 10) |
| **Johny Nguyen** | During **W, 2pm** discussion sections and **W, 12-1pm** on Zoom ([book](https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ1WvcYtgNkM4YyT0kNVwXJozy4e8Q_38ggQFCpD8pPgP1ppncu73eGhm8SXFO1UgkTubgojQ5Vu))|
| **Parinita Saha** | During **F, 4pm** discussion section and **F, 3-4pm** on Zoom ([book](https://calendar.app.google/HLzdroXxskiB1rtx8))|


## Course Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
