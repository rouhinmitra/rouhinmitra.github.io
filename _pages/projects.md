---
layout: page
title: "Projects"
permalink: /projects/
---

## My Projects

Here are some of my key projects. Click on a project title to see more details:

{% for project in site.projects %}
### [{{ project.title }}]({{ project.url }})

{{ project.description }}
{% endfor %}