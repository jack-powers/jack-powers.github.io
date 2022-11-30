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

## Sales Performance and Reporting of Contracts (SPARC) Implementation, Peabody Australia
**Project description:** In collaboration with [Peter Humphreys Pty Ltd](http://www.peterhumphreys.net/), we developed a custom validation and verification framework for the migration of existing operational data from multiple sources into the SPARC product developed by Peter Humphreys Pty Ltd. This project resulted in significant gains in operational efficiency. Opportunities were also identified and implemented to add value to the data management process.

## Contract Management Tool, Peabody Australia
**Project description:** An application was developed using Microsoft Excel and VBA in collaboration with [Peter Humphreys Pty Ltd](http://www.peterhumphreys.net/) to manage large volumes of contractual information for Peabody Australia. This application integrated seamlessly to the SPARC product (Sales Performance and Reporting of Contracts), and enabled the organisation to implement its governance requirements, mitigate against multiple risks, and increase operational efficiency.

## Hospital Flow Simulation Model, World Bank
**Project description:** In collaboration with [Peter Humphreys Pty Ltd](http://www.peterhumphreys.net/), we developed a custom validation and verification framework and used it to test and debug the stochastic discrete-event hospital simulation model developed jointly by the World Bank and Peter Humphreys Pty Ltd. This model was developed in ExtendSim with a Microsoft Excel front-end dashboard for parameter modification and performance analysis. It was designed to model all aspects of a patient’s journey from admission to discharge while ensuring modularity to allow for smooth implementation in any hospital worldwide. A user manual was also created to ensure optimal use of the system.

## Referee Appointments Management Tool, Football Queensland
**Project description:** Developed a referee appointments management tool for [Football Queensland](https://footballqueensland.com.au/) to assist in tracking referee appointments throughout the season for all state-wide competitions. Tool developed using Microsoft Excel with extensive VBA coding to achieve required functionality, including:
*	Import weekly appointments for all state-wide competitions and track the status of the import - preliminary import for tracking appointments several weeks in advance or final import for historical statistics, and appropriately manage when these appointments are updated
*	Track weekly statistics relating to the number of matches in each competition each referee has officiated, with the option to filter by zone, competition, or referee panel.
*	Track weekly referee appointments according to each club in all competitions, to avoid referees being appointed to the same team several weeks in a row. 
*	Track referee assessor appointments, ensuring each referee receives a fair number of assessments and assessors appointments are fairly distributed. 


## Referee Fitness Tests Garmin Watch App
**Project description:** Developed a Garmin watch app that can run all the FIFA approved fitness tests for football referees. It is available on the [Garmin App Store](https://apps.garmin.com/en-US/apps/93e0e777-9dbf-4e46-b1d8-91d7a70e52e8).

## Arduino Chicken Coop Door Automation
**Project description:** Developed an automation solution to open and close a chicken coop door at predetermined times throughout the day using the Arduino microprocessor platform. Utilised skills in both hardware and software to design circuitry and custom PCBs, as well as appropriately program door behaviour. Future planned developments in this area include automated chicken feed and garden watering solutions, and Wi-Fi enabled automation solutions.  

## Schedula Calendar Google Chrome Extension
**Project description:** A Google Chrome extension developed in JavaScript for football (soccer) referees to create a Google Calendar event from the referee appointment system [Schedula](https://www.schedula.com.au/) for their appointed mataches. Populates the match, time, location, and other appointed match officials in the calander event. Available on the [Chrome Web Store](https://chrome.google.com/webstore/detail/schedula-calendar/kgdeoimicejbagodibjcagiibdppbjhb).


## UEFA Refereeing Assistance Program Viewer
**Project description:** As part of referee development, UEFA release Refereeing Assistance Programs that contain clips and analysis of various match incidents. In the past this has been in the form of a stand alone program. However, recently, a paid application is now required to view the clips. I have developed a simple GUI in Python to view the clips and associated technical decision. Available on [GitHub](https://github.com/jack-powers/UEFA-RAP-Viewer).

*[UEFA]: Union of European Football Associations


##  QUT Master of Philosophy Research Proposal LaTeX Template
**Project description:** I developed a LaTeX template during my Master of Philosophy degree for the Research Proposal milestone. Available on the [Overleaf Template Gallery](https://www.overleaf.com/latex/templates/queensland-university-of-technology-qut-mphil-research-proposal/cbmfdbxqnssy).
