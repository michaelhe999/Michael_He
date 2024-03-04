---
layout: page
title: IAT Web App
description: Flask web app for the purpose of making and executing Implicit Association Tests
img: assets/img/iat.jpg
importance: 2
category: work
related_publications: false
---

The purpose of this project was to develop a tool to make the creation and execution of Implicit Association Tests simple, without having to rely on pre-existing tools such as OpenSesame.  
This project involved learning how to use the Python framework Flask, the SQLite3 database system, and how to actually host web servers. 
The application consists of multiple pages, including home, start, round intros, rounds, and results. 
This is a group project where I was the team lead and did fullstack development for the project.

## Front-end: 
The front-end of the web app is done through HTML and Jinja templates, with Javascript scripts incorporated. No data is saved on the front end;
it only serves as the way to collect responses from the user. 

## Back-end
The back-end consists of Python written in the traditional Flask format to organize the routes that the web app has. 
There are definitions for the front-end to display changing text without cluttering the front-end structure, redirections between different routes for easy looping, and input analysis from the frontend. 
All the data collection and storage is also done in the back-end, with the SQLite database and keyboard input data. All this is then fed through a function to output the final result. 

[Here](https://drive.google.com/file/d/1gF2Z3qYkVQP1lGjJFTVNE4-ZKKI74ORV/view?usp=sharing) is a video of the app functioning, as well as a code explanation. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, the starting screen. Middle, an example question page. Right, the corresponding example answer page.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Hopefully this will be the video once that works.
</div>
