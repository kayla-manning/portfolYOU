---
layout: page
title: "About"
permalink: /about/
weight: 1
---

{% include landing.html %}

# **About Me**

Hi, I am **{{ site.author.name }}**.<br>
I am a junior at Harvard pursuing a joint concentration in Statistics and Government with a secondary in Global Health and Health Policy. 

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>