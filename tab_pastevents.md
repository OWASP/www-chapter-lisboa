---
title: PastEvents
displaytext: Past Events
layout:  null
tab: true
order: 2
tags: lisboa
---

# 2025

{% assign page_event_2025 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'events/2025'" | reverse %}

{% for page in page_event_2025 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
  {% endfor %}

# 2024

{% assign page_event_2024 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'events/2024'" | reverse %}

{% for page in page_event_2024 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
  {% endfor %}

# 2023

{% assign page_event_2023 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'events/2023'" | reverse %}

{% for page in page_event_2023 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
  {% endfor %}

# 2022

{% assign page_event_2022 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'events/2022'" | reverse %}

{% for page in page_event_2022 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
  {% endfor %}