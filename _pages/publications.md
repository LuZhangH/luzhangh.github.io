---
layout: page
permalink: /research/
title: Research
description:
years: [2020]
nav: true
---



<br>

<div id="container">
    <div class="myheader">
    <p>Publications & Preprints</p>
    </div>
</div>


<!-- ### Publications & Preprints -->

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>



--- 
<div id="container">
    <div class="myheader">
    <p> Talks </p>
    </div>
</div>


<!-- ### Talks -->

- Floodgate: Inference for Model-Free Variable Importance, [Bernoulli-IMS One World Symposium](https://www.worldsymposium2020.org/), August 2020
	- [Accompanying poster](../assets/floodgate/OWS_Floodgate_Poster.pdf)


--- 

<!-- ### Ongoing Projects -->
<div id="container">
    <div class="myheader">
    <p> Ongoing Projects </p>
    </div>
</div>
- StarTrek: Exploration of Hubs in Graphical Models with False Discovery Rate Control, with [Prof. Junwei Lu](https://junwei-lu.github.io)


