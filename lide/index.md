---
title: Lidé
layout: default
style: portrets
description: Základní informace o jednotlivých pirátech. Přidáš se k nám?
keywords: lide, piráti, podpora
---
{% for person in site.data.my_people %}
<img src="/images/people/{{person}}.jpg" alt="{{ site.data.people[person].name }} - foto" class="left" />

### {{ site.data.people[person].name }}
*{{site.data.people[person].whoami}}*

{{site.data.people[person].about}}

  {% if site.data.people[person].email %}<a href="mailto:{{site.data.people[person].email}}"><i class="fa fa-envelope-o"></i></a>
  {% endif %}{% if site.data.people[person].web %}<a href="{{site.data.people[person].web}}"><i class="fa fa-external-link"></i></a>
  {% endif %}{% if site.data.people[person].facebook %}<a href="{{site.data.people[person].facebook}}"><i class="fa fa-facebook-square"></i></a>
  {% endif %}{% if site.data.people[person].googleplus %}<a href="{{site.data.people[person].googleplus}}"><i class="fa fa-google-plus-square"></i></a>
  {% endif %}{% if site.data.people[person].twitter %}<a href="{{site.data.people[person].twitter}}"><i class="fa fa-twitter"></i></a>
  {% endif %}{% if site.data.people[person].github %}<a href="{{site.data.people[person].github}}"><i class="fa fa-github"></i></a>
  {% endif %}

***
  {% endfor %}


### Kandidáti do krajských voleb

1. AAA
2. BBB
3. CCC
4. DDD
5. EEE

