---
title: Team
nav:
  order: 2
  tooltip: About our team
---
# {% include icon.html icon="fa-solid fa-users" %} Team

{% include section.html %}

## Current members

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and role != 'alumni'" %}

## Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}