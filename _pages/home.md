---
title: "Simulation of European Politics"
layout: splash
permalink: /
date: 2017-10-15 01:48:41 -04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-meu2015.jpg
  cta_label: "Join Our Network"
  cta_url: "http://forum.beta-europe.org"
  caption: "Photo credit: [**MEUS 2015**](http://www.meu-strasbourg.org)"
excerpt: "Bringing Europeans Together Association Netherlands, BETA Netherlands for short, is a politically independent and non-profit association to support the organisation of European politics simulations."
intro_01:
  - title: Our Association
    image_path: /assets/images/BETA-GA_2015.jpg
    alt: "BETA General Assembly 2015"
    excerpt:
    |
      BETA Netherlands is a young, politically independent and non-profit association founded in 2018 by young Europeans in Delft, Netherlands.
    url: "/contact/"
    btn_label: "People behind BETA"
    btn_class: "btn--primary"
intro_02:
  - title: Our Mission
    image_path: /assets/images/MEUS2016_1.jpg
    alt: "Model EU in Strasbourg 2016"
    excerpt:
    |
      Our main goal is to promote mutual understanding and cooperation between young Europeans and to contribute to the spreading of European ideas. It aims to achieve this goal by organising political simulations on local, regional and European level that mirror the functioning of the institutions of the EU end the legislative procedure of the EU for educational purposes.
    url: "/about/"
    btn_label: "About Us"
    btn_class: "btn--primary"
intro_03:
  - title: Our Work
    image_path: /assets/images/MEUS2017_2.JPG
    alt: "Conference Chairs of Model EU Strasbourg 2017"
    excerpt:
    |
      To pursue these goals, BETA Netherlands organises simulations of the European legislative procedure called “Model European Union (MEU)”. BETA Netherlands is an official member of federal association BETA Europe. Over the years, BETA Europe has acquired a large and consistently increasing network of partner organisations that organise MEU conferences in various countries.
    url: "/calendar/"
    btn_label: "Conference Calendar"
    btn_class: "btn--primary"

---

{% include feature_row id="intro_01" type="left" %}

{% include feature_row id="intro_02" type="right" %}

{% include feature_row id="intro_03" type="left" %}

<div class="layout--splash__recent--posts">
<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}
</div>
