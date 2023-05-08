---
title: Home Page
layout: main
products:
    - Product 1
    - Product 2
    - Product 3
tags: [ mainnav ]
---
## Created for Firebase

This is a test Eleventy Site (Aidan)

{% for product in products %}
- {{ product }}
{% endfor %}


