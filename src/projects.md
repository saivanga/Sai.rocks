---
layout: post-minimal.njk
title: Projects
eleventyExcludeFromCollections: true
---

{% for project in projects %}

<p></p>

### {{project.title}}

##### {{project.date}}

{% for link in project.links %}

- [{{ link.name }}]({{ link.link }})

{% endfor %}

<p>{{project.description}}</p>
{% endfor %}
