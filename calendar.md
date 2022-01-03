---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

A tentative plan for the schedule (topics, deadlines, etc.) is available [here](https://docs.google.com/spreadsheets/d/1YJQVkr_j-k0zsgNZ0fYbNI6ECc8P5-3V-GuGbEy5GKQ/edit?usp=sharing).


{% for module in site.modules %}
{{ module }}
{% endfor %}
