---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab is made up of collaborative, interdisciplinary and engaged researchers. We foster a supportive environment where science can serve as an enterprise for personal and collective growth. The team include postdocs, PhD & undergraduate students nad staff. 

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include grid.html style="square" content=content %}
