---
layout: default
title: About
---
## About Me

<center>
<img class="user-avatar" src="{{ site.owner.avatar }}" width="250" height="250">
</center>

<br/>

Hello.

My name is Ichroman Raditya Duwila, most of my family and friends call me **Didit**. I am a software developer 
living in Indonesia, who also passionate in photography and travelling as well. I love reading too.

My main programming language to use in daily basis is Java, which I have used for around 3 years. Lately, I also
learn Groovy, Kotlin and Angular. 

Currently I work as a Java developer for PT. Aprisma Wirecard.

Cheers!

<div class="pagination">
  {% if site.owner.linkedin %}
    <a href="{{ site.owner.linkedin }}" class="social-media-icons"><i class="fa fa-2x fa-linkedin-square" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.email %}
    <a href="mailto:{{ site.owner.email }}" class="social-media-icons"><i class="fa fa-2x fa-envelope-square" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.twitter %}
    <a href="https://twitter.com/{{ site.owner.twitter }}" class="social-media-icons"><i class="fa fa-2x fa-twitter-square" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.github %}
    <a href="{{ site.owner.github }}" class="social-media-icons"><i class="fa fa-2x fa-github-square" aria-hidden="true"></i></a>
  {% endif %}
</div>
