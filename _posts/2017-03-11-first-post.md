---
layout: single
author_profile: true
read_time: true
comments: 
share: true
related: true
title: First Post
date: '2017-03-11T00:27:37+00:00'
---
Images are cool

{% include trinket-open type='python' %}
import turtle

tina = turtle.Turtle()

for c in ['red', 'green', 'yellow', 'blue']:
    tina.color(c)
    tina.forward(75)
    tina.left(90)

tina.penup()
tina.backward(100)
tina.write("Hello world!")
{% include trinket-close %}
