---
layout: default
title: My hardware
permalink: /hardware
---
# My hardware

{% for item in site.data.hardware.hardware %}
## {{ item.title }}
{{ item.description }}
{% endfor %}
