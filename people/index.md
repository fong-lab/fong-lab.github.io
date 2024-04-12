---
title: People
nav:
  order: 2
  tooltip: 
---

# {% include icon.html icon="fa-solid fa-people-group" %}People

{% include section.html %}

## Professor

{% include list.html  data="members"  component="portrait"  filters="role: prof" %}

{% include section.html %}

## Current Members

{% include list.html  data="members"  component="portrait"  filters="role: current-phd&ms" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-ms" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-undergrad" %}
<!--
{% include list.html  data="members"  component="portrait"  filters="role: pi" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-manager" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-technician" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-postdoc" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-phd" %}
{% include list.html  data="members"  component="portrait"  filters="role: current-hs" %}
-->

{% include section.html blue=true %} 
### N2SL is looking for motivated undergraduate/graduate students who are interested in networks and systems. Please send an email to Prof. Im if you want to work with us.



{% include section.html %}

## Alumni

{% include list.html  data="members"  component="portrait"  filters="role: alum" %}

