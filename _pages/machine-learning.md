---
layout: archive
permalink: /machine-learning/
title: Machine Learning
author: Arup Bhunia
author_profile: false
description: "Its Machine learning !!"
og_image: "/images/perceptron/percept.jpg"
---

Go ahead, [read on!]({{ site.baseurl }}{% link _pages/machine-learning.markdown %})

## Latest stories

<div class="grid__wrapper">
  {% assign collection = 'machine-learning' %}
  {% assign posts = site[collection] | reverse %}
  {% for post in posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>