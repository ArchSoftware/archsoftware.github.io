---
layout: page
title: About
permalink: /about/
---

### Our story

ArchSoftware has been founded by Sebastiano Galeazzo (arch-dev) the 7th of March in 2020.

Our objective is to fill the gap between modern engineering softwares available on computer only and mobile devices by building applications focused on design, accuracy and reactivity.

### Out team

<div class="grid_layout">
{% for person in site.data.people %}
    {% include components/card.html
        title = person.name
        description = person.bio
        github = person.github
    %}
{% endfor %}
</div>