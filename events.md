---
layout: default
title: "Events"
---

## Events

{% for event in site.data.events %}
  <p><a href="{{event.url}}">{{event.title}} by {{event.author}}, {{event.location}}, {{event.date}}</a></p>
{% endfor %}
