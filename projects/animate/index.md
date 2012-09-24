---
layout: default
title: Exploring Non-Linear Path Animations
group: projects
---
{% include JB/setup %}

<h3>{{ page.title }}</h3>
<br/>

The project has various demos designed to explore building components to support
a custom animations with various animation engines over large sets of elements on non-linear paths.

You can read more about this these tests [on my blog]({{ site.blog_url}}). 

#### Demo Pages  
  
<ul class="pages">
   {% assign pages_list = site.pages %}
   {% assign group = 'animate' %}
   {% include JB/pages_list %}
</ul>