---
layout: post-minimal.njk
title: Projects
eleventyExcludeFromCollections: true
---

{% for project in projects %}

<p></p>

##### {{project.date}}

### {{project.title}}

<p>{{project.description}}</p>

{% for link in project.links %}

[{{ project.link.name }}]({{ project.link.link }})

{% endfor %}
