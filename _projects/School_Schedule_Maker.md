---
layout: page
title: School Schedule Maker
description: MERN stack web app to facilitate the making of UCSD course schedules
img: assets/img/scheduler.jpg
importance: 2
category: work
related_publications: false
---

The purpose of this project was to create a MERN stack web app that made UCSD class schedules easier to create. We had a 10 week timeframe within which to create this app. 

This project involved learning how to use the various tools of the MERN stack, where I largely used MongoDB to store data and Compass to easily verify code actions, Node.js for creating the back-end, and Postman to test routing. 

The application consists of a well-designed front-end interface where students can create accounts, which are stored in the database, to be able to repeatedly access their data. From their account, students can then select the classes they wish to take, the teachers they would like, as well as block out various times where they have other events and can't have class. Upon submission, this data is sent to the back-end which processes all the requests and outputs a list of schedules that they can actually have, including multiple possible discussion or lecture sections. 

This is a group project where I was a back-end developer mostly responsible for the sign-up/sign-in system and the schedule maker algorithm. 

## Back-end
The log-in system is a relatively simple implementation, with some password hashing for security purposes. However, the sign-in was not a high priority as we had a tight deadline. 

The scheduling algorithm is similar to the job-sequencing algorithm, but with a lot more requirements and restraints. For example, students were able to select times where they had no time for class, and other times where they didn't want class, referred to as a blacklist and a graylist respectively. The algorithm I ended up creating started by attempting to avoid all blacklist and graylist times, but if that wasn't possible, tried to use as few graylist times as possible. 

Another issue was the vast time complexity of all of these operations. With each class having several sections, each section having different discussion times, and a variety of formats in the ways times were written out, the number of time comparisons that had to be made to check conflicting times was extremely large, especially considering that there was technically no upper limit on the number of courses that could be input. 

