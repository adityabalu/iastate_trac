---
title: "Events"
layout: default
excerpt: "events"
sitemap: false
permalink: /events.html
---

# News

{% for event in site.data.events %}
  <p>{{ event.date }} <br>
  <em>{{ event.description }}</em></p>
  {% endfor %}

# see news.yml for reference