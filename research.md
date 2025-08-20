---
layout: page
title: research
permalink: /research/
horizontal: true
---

<hr>
<!-- pages/projects.md -->
<div class="projects">
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
    <div class="container">
      {%- for project in sorted_projects -%}
        {% include projects_main.html %}
        <hr>
      {%- endfor %}
    </div>
</div>