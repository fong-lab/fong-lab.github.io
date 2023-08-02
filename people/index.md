---
title: People
nav:
  order: 2
  tooltip: 
---

# {% include icon.html icon="fa-solid fa-users" %}People

{% include section.html %}

## Current Members

{% include list.html  data="members"  component="portrait"  filters="role: pi" %}
{% include list.html  data="members"  component="portrait"  filters="role: manager" %}
{% include list.html  data="members"  component="portrait"  filters="role: technician" %}
{% include list.html  data="members"  component="portrait"  filters="role: postdoc" %}
{% include list.html  data="members"  component="portrait"  filters="role: phd" %}
{%  include list.html  data="members"  component="portrait"  filters="role: undergrad" %}
{%  include list.html  data="members"  component="portrait"  filters="role: hs" %}


{% include section.html %}

## Alumni

{%  include list.html  data="members"  component="portrait"  filters="role: alum" %}

