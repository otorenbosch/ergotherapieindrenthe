---
layout: page
title: Deelnemers
menu: true
order: 2
---

## Ergotherapeuten in Drenthe

Hieronder vindt u alle ergotherapeuten die deelnemen aan ons netwerk, verspreid door heel Drenthe.

<div class="deelnemers-grid">
  {% for deelnemer in site.deelnemers %}
  <div class="deelnemer-card">
    {% if deelnemer.logo %}
      <img src="{{ deelnemer.logo }}" alt="{{ deelnemer.title }} logo">
    {% endif %}
    <h3>{{ deelnemer.title }}</h3>
    {% if deelnemer.website %}
      <a href="{{ deelnemer.website }}" target="_blank">Bezoek website</a>
    {% endif %}
    {{ deelnemer.content }}
  </div>
  {% endfor %}
</div>

*Bent u ergotherapeut in Drenthe en wilt u aansluiten? Neem contact met ons op!*