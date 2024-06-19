---
layout: page
title: IAT Web App
description: Flask web app for the purpose of making and executing Implicit Association Tests
img: assets/img/iat.jpg
importance: 2
category: work
related_publications: false
---

The purpose of this project was to develop a tool to make the creation and execution of Implicit Association Tests simple, without having to rely on pre-existing tools such as OpenSesame. The issue with a tool like OpenSesame is that it only runs if the required files are downloaded, and while the actual creation process is simple, it relies on having to understand the tool rather than using something that programmers are more familiar with. 
This project involved learning how to use the Python framework Flask, the SQLite3 database system, and how to actually host web servers. 
The application consists of multiple pages, including home, start, round intros, rounds, and results. 
This is a group project where I was the project lead and did full-stack development for the project.

## Front-end: 
The front-end of the web app is done through HTML and Jinja templates, with Javascript scripts incorporated. No data is saved on the front end;
it only serves as the way to collect responses from the user. 

## Back-end
The back-end consists of Python written in the traditional Flask format to organize the routes that the web app has. 
There are definitions for the front-end to display changing text without cluttering the front-end structure, redirections between different routes for easy looping, and input analysis from the front-end. 
All the data collection and storage is also done in the back-end, with the SQLite database and keyboard input data. All this is then fed through a function to output the final result. 

Since this was a project as part of a research group, no further details can be shared. 
