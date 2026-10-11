---
layout: default
title: Hidden Berkeley: A Newcomer's Guide
---

# Hidden Berkeley: A Newcomer's Guide

Welcome to UC Berkeley! This guide is designed to help new students and visitors discover hidden campus gems and essential everyday services. From peaceful reading spots to campus support locations, explore these helpful resources to make the most of your time at Berkeley.

<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.

