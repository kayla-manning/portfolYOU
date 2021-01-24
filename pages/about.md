---
layout: page
title: "About"
permalink: /about/
weight: 1
---

{% include landing.html %}

# **About Me**

Hi, I am **{{ site.author.name }}** :wave:,<br>
I am a junior at Harvard pursuing a joint concentration in Statistics and Government with a secondary in Global Health and Health Policy. Above all, I am passionate about applying data science and quantitative principles to problems in social science.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>