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
{% endfor %}

{% for link in project.links %}

- {{% link.link %}}

  {% endfor %}

<!-- <div class="projects">
	<p class="project-date">{{project.date}}</p>
	<h4>{{project.title}}</h4>
	<p>{{project.description}}</p>

    {% for link in project.links %}

- [Demo]({{link.link}})

</div>
{% endfor %} -->
