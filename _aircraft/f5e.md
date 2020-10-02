---
title: F-5E
---

This page is about F5e.

<!-- filter somehow? data files? -->

Available bombs:
{% for weapon in site.weapons %}
- [{{ weapon.name }}]({{ weapon.url }})
{% endfor %}

Sensors:
{% assign radar = site.sensors
    | where: "name", "apq159v3"
    | first %}
- [{{ radar.name }}]({{ radar.url }})
