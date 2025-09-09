---
layout: page
title: people
permalink: /people/
horizontal: true
---

<hr>
<!-- pages/people.md -->
<div class="people">
  {%- assign sorted_people = site.people | sort: "importance" -%}
    <div class="container">
      {%- for project in sorted_people -%}
        {% include projects_main.html %}
        <hr>
      {%- endfor %}
    </div>
</div>