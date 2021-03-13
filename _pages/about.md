---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a PhD candidate in [HPDC group](https://www.vuhpdc.net) at VU University, Amsterdam under the supervision of [Prof. Henri Bal](https://www.cs.vu.nl/~bal/) and [Lin Wang](https://linwang.info/). I am currently working on systems (probably at the edge) for video stream analytics, which falls at the intersection of systems research, computer vision using deep learning and edge computing. My research is funded by NWO, Netherlands Organisation for Scientific Research as a part of [Efficient Deep Learning](https://www.nwo.nl/en/research-and-results/programmes/perspectief/perspectief+programmes/2017/edl) programme.

I did my Masters in parallel and distributed computer systems [(PDCS)](https://masters.vu.nl/en/programmes/parallel-distributed-computer-systems/index.aspx) from VU University, Amsterdam with *Cum Laude*. I have around four years of industrial experience in computer systems, particularly distributed and data storage systems.

<h2 class="notice--info"> Note: </h2> I am open for a research internship at a university or industrial lab in the area of video stream analytics, systems for DL at the edge. If you find my profile or work interesting then please shoot an email.

<header>
<h1 class="page__title" itemprop="headline" id="patents">Patents
</h1>
</header>
<ul>
{% for post in site.patents reversed %}
  {% include patents.html %}
{% endfor %}
</ul>


<header>
<h1 class="page__title" itemprop="headline" id="publications">Publications</h1>
</header>
<ul>
{% for post in site.publications reversed %}
  {% include publications.html %}
{% endfor %}
</ul>

<header>
<h1 class="page__title" itemprop="headline" id="theses">Theses
</h1>
</header>
<ul>
{% for post in site.theses reversed %}
  {% include theses.html %}
{% endfor %}
</ul>

