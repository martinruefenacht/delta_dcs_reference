---
title: F-5E
---

This page is about F5e.

<details>
    <summary>Procedures</summary>

    <details>
        <summary>Engine Start Procedure</summary>
    </details>
    
    <details>
        <summary>PreTaxi Procedure</summary>
    </details>

    <details>
        <summary>Takeoff Procedure</summary>
    </details>

    <details>
        <summary>Engine Relight</summary>
    </details>
</details>

<!-- <input type="checkbox" id="horns" name="horns"> -->


<!-- filter somehow? data files? -->

Available bombs:
{% for weapon in site.weapons %}
- [{{ weapon.name }}]({{ weapon.url }})
{% endfor %}

Available missiles:
...

Sensors:
{% assign radar = site.sensors
    | where: "name", "apq159v3"
    | first %}
- [{{ radar.name }}]({{ radar.url }})

Navigation systems:
...

general information

cockpit overview

engine information
