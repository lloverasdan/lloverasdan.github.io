---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

### About me

{% for member in site.data.pi %}
<div class="jumbotron">
<div class="row">
<div class="col-sm-4">
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" width="100%" style="max-width:250px"/>
</div>
<div class="col-sm-8 col-xs-12">
  <h3>{{ member.name }}</h3>
  <h4><i>{{ member.info }}</i></h4>
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %}

  <ul style="overflow: hidden">
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education4 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 5 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education4 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education5 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 6 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education4 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education5 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education6 | replace: "-","&#8211;"}} </li>
  {% endif %}
  </ul>
</div>
</div>
</div>
{% endfor %}

<div class="jumbotron">
### *Background*

I am currently doing a postdoc at the Naval Research Laboratory, a position I began in January 2024. My research focuses on the predictability of polar lows. My advisor is Dr. Jim Doyle.

I earned my PhD from the University of Washington in 2023. My research dealt with atmospheric predictability, specifically focusing on the initial-condition errors that lead to poor forecasts of midlatitude cyclones. I used WRF simulations of both idealized and real-world cyclones to conduct my experiments. My advisor was Professor Dale Durran.

I completed my MS at the University of Washington in 2021. For my MS thesis, I compared initial-condition-error growth in idealized midlatitude cyclones with that of homogeneous, isotropic turbulence, which is the context in which Lorenz observed the "butterfly effect".

I completed my BS at the University of Miami in 2018. For my senior thesis, I investigated the effect of shortwave-absorbing smoke particles on low-cloud cover over the southeast Atlantic Ocean. I also completed a summer research internship at the Geophysical Fluid Dynamics Laboratory, where I studied the predictability of summertime precipitation over the southeastern United States.

</div>

<div class="jumbotron">
### *Goals*

Broadly speaking, my goal is to use my background in meteorology and numerical modeling to contribute to the improvement of weather and climate predictions that are vital to lives and property. More specifically, I am interested in conducting research on the limits to atmospheric predictability and identifying the actions (if any) that can be taken to extend these limits.

I am also passionate about service and teaching. I am currently on the AMS Committee on Weather Analysis and Forecasting, and I served as the Graduate President of the UW AMS student chapter from 2020--2022. I also was the UW WxChallenge team manager from 2020--2023. I was the instructor or teaching assistant for numerous undergraduate courses at the University of Washington, including classes on hurricanes and thunderstorms, weather analysis and forecasting, and climate change. As a teacher, I am committed to engaging students with a wide variety of learning styles.

</div>

<div class="jumbotron">
### *Personal*

I am originally from Clearwater, Florida. In my free time, you can find me weightlifting, reading, and cheering on my favorite college and professional sports teams.

</div>
