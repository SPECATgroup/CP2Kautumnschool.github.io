---
layout: page
---

<link rel="stylesheet" href="{{ '/css/style.css' | relative_url }}">
<!-- <img src="/images/logo.png" width="125%"> -->
![Alt text]({{ "/images/logo.png" | relative_url }})


## **International Autumn School CP2K-Newton-X-WaveMixings for mixed classical-quantum dynamics**

## About the Autumn School

This autumn schools aims to give an overview on (non-)adiabatic mixed excited-state dynamics using the program packages
<a href="https://www.cp2k.org">**CP2K**</a>, <a href="https://newtonx.org">**Newton-X**</a> and <a href="https://gitlab.com/apolionl/WaveMixings.jl">**WaveMixings**</a> to educate graduate students, postdocs, researchers, and educators working in
computational chemistry. 
Focus of the autumn school is to complement **expert-led lectures** covering the underlying theory with practical **hands-on training** on cutting-edge HPC systems. Participants will be given the opportunity to present own research and network with leading scientists during the **poster session**. 

Topics range from fundamental concepts to advanced techniques of (non-)adiabatic mixed quantum-classical molecular
dynamics, summarized by the following keywords:

- (Non-)adiabatic molecular dynamics
- Excited states
- Quantum-classical dynamics
- Trajectory surface hopping, Ehrenfest dynamics
- Time-dependent density functional theory
- Bethe-Salpeter equation, GW
- Machine learning
- High-performance computing

## Registration

**The international autumn school will take place in Kiel, Germany, from October 14 to 16, 2026. We will also provide
the option to participate in the autumn school remotely.**

**Registration is <a href="https://docs.google.com/forms/d/1nFZT4d2HzpynXbHAE5N_bu-hD8Jp9S20ROLkLkGQ_YY/">open</a>** on a first-come, first-served basis. 
This course is free of cost for members of German universities or publicly-funded research institutions. Please register the course using your university/institutional e-mail address.

The event is funded by the <a href="https://www.international.uni-kiel.de/en/internationalisation-fund">CAU fund for Internationalisation</a>, providing limited **financial support to cover travel costs of participants**. To apply for financial support, please submit a brief letter of motivation and a resume. Please comment on your current research interests and the expected benefit to be gained by participating in this autumn school.  


## Schedule

The current schedule may be changed. Please check for updates. 


## Our team

| Name            | Affiliation         |
| --------------- | ------------------- |
| [Prof. Mario Barbatti](https://barbatti.org/about/) | University Aix-Marseille, France |
| [Dr. Philipp Schienbein](https://schienbein.eu) | Ruhr-University Bochum, Germany |
| [Dr. Ritama Kar](https://barbatti.org/about/)      |   University Aix-Marseille, France (Group M. Barbatti) |
| [Dr. Rafael S. Mattos ](https://barbatti.org/about/)   | University Aix-Marseille, France (Group M. Barbatti) |
| [Dr. Stepan Marek](https://www.uni-regensburg.de/en/physics/wg/computational-electronic-structure-theory/team/stepan-marek) | University Regensburg, Germany (Group J. Wilhelm) |
| [Dr. Luis Vasquez](https://scholar.google.com/citations?user=KG6dxGcAAAAJ&hl=en) | Hangzhou Dianzi University, China (Group M. Gelin) |
| [Prof. Anna Hehn](https://www.hehn.phc.uni-kiel.de/en) | Christian-Albrechts-University Kiel, Germany |
| [Dr. Ole Schütt](https://ole.schuett.name) | CP2KLab, Zurich, Switzerland |


## Ressources

| Software | Links |
|----------|-------|
| Newton-X | [Official website](https://newtonx.org/) | [Tutorials](https://osf.io/w4dkc/)  | [Manual](https://www.univie.ac.at/newtonx/nx-docs-2_2.pdf) |
| CP2K | [Official website](https://www.cp2k.org/) | [Tutorials](https://www.cp2k.org/exercises:common:index) |[Manual](https://manual.cp2k.org/trunk/) |


## Venue

The autumn school will take place at the <a href="https://wissenschaftszentrumkiel.de">Wissenschaftszentrum</a> in Kiel, Fraunhoferstrasse 13, 24118 Kiel.  

The campus map of Christian-Albrechts-University Kiel can be found <a href="https://www.uni-kiel.de/en/university/building-sites-campus-development/maps-directions">here</a>. The Wissenschaftszentrum is marked on the map
next to the Wissenschaftspark. Note that the car park "Tesla-Haus" is right next to the event venue.

<p id="where">
  Get directions with
  <a href="//www.openstreetmap.org/?mlat={{54.3417133}}&mlon={{10.1221628}}&zoom=16">OpenStreetMap</a>
  or
  <a href="https://maps.app.goo.gl/HrQR63VpC18Tca6x8">Google Maps</a>.
</p>

If you need further information about travel and accommodation, feel free to contact us. Please note that the relevant costs are your responsibility.

## Repository / Videos

All lecture material and video recordings will be provided via the <a href="https://www.youtube.com/kieluni">youtube channel of the Christian-Albrechts-University Kiel</a>.
Lecture material for the hands-on sessions will be provided via the <a href="https://cau-git.rz.uni-kiel.de/hpc/cp2k-newtonx_autumn_school">autumn school's Gitlab account</a> as well as via the corresponding <a href=" ">Github repository</a>.

## Additional information

Please bring your own laptop (Windows, MacOS, or Linux) for the hands-on tutorials.
The number of seats and poster presentation slots are limited and the allocations are managed by the organizers.

## Acknowledgements

We gratefully acknowledge support by the <a href="https://www.international.uni-kiel.de/en/internationalisation-fund">CAU funds for internationalisation</a>. 

![Alt text]({{ "/images/cau_logo_smaller.png" | relative_url }}) ![Alt text]({{ "/images/Kinsis_logo_smaller.png" | relative_url }})
<!-- <img src="/images/cau_logo.png" width="45%"> ![Alt text]({{ "/images/kinsis_logo.png" | relative_url }}) -->

## Contact

{% comment %}
CONTACT EMAIL ADDRESS
Display the contact email address set in the configuration file.
{% endcomment %}
<p id="contact">
  Please email
  {% if page.email %}
  {% for email in page.email %}
  {% if forloop.last and page.email.size > 1 %}
  or
  {% else %}
  {% unless forloop.first %}
  ,
  {% endunless %}
  {% endif %}
  <a href='mailto:{{email}}'>{{email}}</a>
  {% endfor %}
  {% else %}
  hehn@pctc.uni-kiel.de ; specathehn@gmail.com
  {% endif %}
  for more information.
