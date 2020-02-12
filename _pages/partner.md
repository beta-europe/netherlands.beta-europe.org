---
layout: archive
title: "Our Partners"
permalink: /partner/
author_profile: false

sidebar:
  - title: Become a Partner
    # image: "/assets/images/beta-logo-180-transparent.png"
    # image_alt: Logo of BETA Europe
    text:
      |
        Please [contact us](mailto:netherlands@beta-europe.org) to learn more about partnerships.
---

MEU Netherlands would not be possible without our partners.

{% include map.html geojson="/partners.geojson" %}

{% include base_path %}

<div class="grid__wrapper grid__partners">
  {% for post in site.partners %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
