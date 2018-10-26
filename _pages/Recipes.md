---
layout: archive
permalink: /recipes/
title: Why cooking is important
author_profile: true
---

Being on the road is always amazing, and I travel as much as I can. Other times, I try to be exploratory mentally by experiencing food from different regions. Compared with going to exotic restaurants, I prefer to learn how to cook nonnative dishes. The process of cooking involves the coordination between eyes, nose, ears, mouth, hand, and mind. It is a ritual for me to relax and reflect, and gives me a feeling of peace and fulfillment. Cooking inspires me to appreciate the cultures with which I am not familiar with. 

## Recipes

<div class="grid__wrapper">
  {% assign posts = site.recipes %}
  {% for post in posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>