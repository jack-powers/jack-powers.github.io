---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
modified: 2021-12-24

# redirect_from: 
#   - /projects.html
---

{% include base_path %}


{% for post in site.projects1 %}
  {% include archive-single.html %}
{% endfor %}


## Arduino Chicken Coop Door Automation
**Project description:** Developed an automation solution to open and close a chicken coop door at predetermined times throughout the day using the Arduino microprocessor platform. Utilised skills in both hardware and software to design circuitry and custom PCBs, as well as appropriately program door behaviour. Future planned developments in this area include automated chicken feed and garden watering solutions, and Wi-Fi enabled automation solutions.  


## Schedula Calendar Google Chrome Extension
**Project description:** A Google Chrome extension developed in JavaScript for football (soccer) referees to create a Google Calendar event from the referee appointment system [Schedula](https://www.schedula.com.au/) for their appointed mataches. Populates the match, time, location, and other appointed match officials in the calander event. Available on the [Chrome Web Store](https://chrome.google.com/webstore/detail/schedula-calendar/kgdeoimicejbagodibjcagiibdppbjhb).


## UEFA Refereeing Assistance Program Viewer
**Project description:** As part of referee development, UEFA release Refereeing Assistance Programs that contain clips and analysis of various match incidents. In the past this has been in the form of a stand alone program. However, recently, a paid application is now required to view the clips. I have developed a simple GUI in Python to view the clips and associated technical decision. Available on [GitHub](https://github.com/jack-powers/UEFA-RAP-Viewer).

*[UEFA]: Union of European Football Associations


##  QUT Master of Philosophy Research Proposal LaTeX Template
**Project description:** I developed a LaTeX template during my Master of Philosophy degree for the Research Proposal milestone. Available on the [Overleaf Template Gallery](https://www.overleaf.com/latex/templates/queensland-university-of-technology-qut-mphil-research-proposal/cbmfdbxqnssy).
