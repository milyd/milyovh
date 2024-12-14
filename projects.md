---
layout: default
title: Projects
permalink: /projects
---
# Projects

{% for item in site.data.projects.projects %}
## {{ item.title }}
{{ item.description }}  
Website: [{{ item.website }}]({{ item.website }})
{% endfor %}
