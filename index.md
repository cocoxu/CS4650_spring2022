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
- [Piazza](https://piazza.com/gatech/spring2022/cs4650a) (announcements, questions, discussion)
- [Gradescope](https://www.gradescope.com/courses/345683) (homework assignments, submission, and grading)
- [Canvas](https://canvas.gatech.edu/) (only used for Bluejeans recordings and tracking late days)

{% for module in site.modules %}
{{ module }}
{% endfor %}
