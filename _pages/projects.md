---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
modified: 2016-06-06

# redirect_from: 
#   - /projects.html
---

{% include base_path %}


{% for post in site.projects1 %}
  {% include archive-single.html %}
{% endfor %}




##  QUT Master of Philosophy Research Proposal LaTeX Template
**Project description:** I developed a LaTeX template during my Master of Philosophy degree for the Research Proposal milestone. Available on the Overleaf [Template Gallery](https://www.overleaf.com/latex/templates/queensland-university-of-technology-qut-mphil-research-proposal/cbmfdbxqnssy).



## Google Chrome Calander Extension
**Project description:** A Google Chrome extension developed in JavaScript for football (soccer) referees to create a Google Calendar event from the referee appointment system Schedula for their appointed mataches. Populates the match, time, location, and other appointed match officials in the calander event. Available on the [Chrome Web Store](https://chrome.google.com/webstore/detail/schedula-calendar/kgdeoimicejbagodibjcagiibdppbjhb).


## UEFA Refereeing Assistance Program Viewer
**Project description:** As part of referee development, UEFA release Refereeing Assistance Programs that contain clips and analysis of various match incidents. In the past this has been in the form of a stand alone program. However, recently, a paid application is now required to view the clips. I have developed a simple GUI in Python to view the clips and associated technical decision. Available on [GitHub](https://github.com/jack-powers/UEFA-RAP-Viewer).