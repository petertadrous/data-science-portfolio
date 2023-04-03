---
layout: page
title: About
permalink: /about/
order: 3
---

# **About Me**

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Technologies" source=site.data.technologies-skills %}
{% include about/skills.html title="Statistics & ML" source=site.data.statistics-ml-skills %}
</div>

<div class="row">
{% include about/education-timeline.html %}
</div>

<div class="row">
{% include about/employment-timeline.html %}
</div>
