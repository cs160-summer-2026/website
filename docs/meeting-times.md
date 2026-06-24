---
layout: page
title: Meeting times
description: The weekly event schedule.
---

# Meeting times

## Office hours:

- **Mina**: Thursday, 9:00 AM – 10:00 AM, [on Zoom by Appointment](https://calendar.app.google/Us8PP2n88o5iuWnH9)
- **Selaine**: TBD
- **Ananya**: Thursday, 8:00 AM – 9:00 AM, on Zoom by Appointment
- **Vivian**: TBD
- **Arhaan**: TBD

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
