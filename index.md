---
layout: home
title: Index page (Home)
drink-type: "https://www.loveandlemons.com/matcha-green-tea/"
---  

# Caffeine Overdose page

## Description
{{ site.description }}  
{% assign lead = site.team_members | where:"role", "rarely" | first %}
What I am drinking right now is {{ lead.name }}.
[See the drinks](about#team)

This goes to the [about page](about)   

Think of a drink!  [what I thought of]({{ page.drink-type}})


