---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}


**Project description:** A Google Chrome extension developed in JavaScript for football (soccer) referees to create a Google Calendar event from the referee appointment system Schedula for their appointed mataches. Populates the match, time, location, and other appointed match officials in the calander event.

Available on the [Chrome Web Store](https://chrome.google.com/webstore/detail/schedula-calendar/kgdeoimicejbagodibjcagiibdppbjhb).