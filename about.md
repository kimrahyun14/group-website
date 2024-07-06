---
layout: default
title: About
---

## About the webpage
I wrote about caffeine overdoses because I am having one

{{ site.description }}  
It's quite hard to focus but I'm doing alright    
I am writing this because otherwise I worry I won't fully learn from the lesson posted

## Caffeinated Drinks

The following drinks are things I like to order:
{% for team_member in site.team_members %}
- {{ team_member.name}}, headache?: {{ team_member.role }}
{% endfor %}

**Enjoy**

