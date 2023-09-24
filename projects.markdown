---
layout: page
title: "Projects"
permalink: /projects/
---

<div class="grid_layout">
{% for project in site.data.projects %}
    {% include components/card.html
        title = project.title
        description = project.description
        href = project.href
    %}
{% endfor %}
</div>