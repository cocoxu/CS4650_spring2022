---
layout: home
title: CS 4650
nav_exclude: true
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

Georgia Institute of Technology

- Instructor: [Wei Xu](https://cocoxu.github.io) 
- Lecture: Mondays, Wednesdays 3:30-4:45pm
{% for module in site.modules %}
{{ module }}
{% endfor %}
