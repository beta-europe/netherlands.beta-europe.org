---
title: Welcome to MEU Netherlands 2020!
layout: splash
permalink: /MEUNL20
date: 2019-01-28 01:48:41 -01:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/delft.jpg
excerpt: ""
intro_01:
  - title: What is an MEU?
    image_path: /assets/images/europeanparliament.jpg
    alt: "European Parliament"
    excerpt:
    |
      An MEU, or Model European Union, is a political simulation where you get to learn about and simulate the inner workings of the European Union institutions, in particular the European Parliament and the Council of the European Union.
intro_02:
  - title: About MEU Netherlands
    image_path: /assets/images/meu2019group.jpg
    alt: "Model EU Netherlands 2019"
    excerpt:
    |
      Our 2020 edition will take place between the **13th and the 16th of July** in the picturesque city of **Delft**, just 15 minutes away from both The Hague and Rotterdam. During the 4-day simulation, you will have the opportunity to debate two exciting legislative proposals, take part in our evening socials, and meet youngsters from all over Europe and beyond.
intro_03:
  - title: Roles Available
    image_path: /assets/images/buecken.jpg
    alt: "Model EU Netherlands 2019"
    excerpt:
    |
      Here at MEU Netherlands, we’ve got something for everyone’s tastes! Take your pick between four roles: Member of the European Parliament, Minister, Lobbyist, or Journalist. As an MEP or Minister, you will debate and propose amendments to two legislative proposals of the European Commission. As a Lobbyist, you will try to influence legislators and push your interests. Finally, as a Journalist, you will have the opportunity to write articles, interview legislators and lobbyists, and gain an insight into the world of political journalism.
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