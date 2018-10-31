---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a PhD candidate in <a href="https://www.cs.vu.nl/en/research/computer-systems/hpdc/" target="_blank">HPC group</a> at VU University, Amsterdam under the supervision of [Prof. Henri Bal](https://www.cs.vu.nl/~bal/). I am working on efficient deep learning for computer vision, at the intersection between deep learning and high performance computing.

I did my Masters in parallel and distributed computer systems <a href="https://masters.vu.nl/en/programmes/parallel-distributed-computer-systems/index.aspx" target="_blank">(PDCS)</a> from VU Univeristy, Amsterdam with *Cum Laude*. I have around four years of industrial experience in computer systems, particularly distributed and data storage systems.

<br>
<header>
<h1 class="page__title" itemprop="headline" id="publications">Publications</h1>
</header>
<ul>
{% for post in site.publications reversed %}
  {% include publications.html %}
{% endfor %}
</ul>

<br>
<header>
<h1 class="page__title" itemprop="headline" id="patents">Patents
</h1>
</header>
<ul>
{% for post in site.patents reversed %}
  {% include patents.html %}
{% endfor %}
</ul>

<br>
<header>
<h1 class="page__title" itemprop="headline" id="theses">Theses
</h1>
</header>
<ul>
{% for post in site.theses reversed %}
  {% include theses.html %}
{% endfor %}
</ul>

