---
layout: page
title: Math Learning App
description: Unity app to teach addition to elementary schoolers in a game-like way
img: assets/img/math.jpg
importance: 1
category: work
related_publications: false
---

The purpose of this project was to learn and practice app development; as a result, a lot of the functions are basic, and I used Unity to make the front-end easier. 
This project involved learning how to code in C#, learning how to use Unity, and learning how users could interact with and use apps. 
The application involves two main aspects: a starting screen and the actual quiz screen. 

## Starting screen
The starting screen consists of text, visual elements, an input field, and two buttons. The input field is used to specify the maximum number used in questions. 
For example, if the input was 4, the highest question displayed would be "What is 4 + 4?". The two buttons toggle between two quiz modes: normal, and assistant mode. 
Normal mode simply displays a question and requests an answer, while assistant mode will summon objects on either side of the question so that learners can count rather than add. 

## Quiz screen
The quiz screen alternates between the question page and the answers page. On the question page, there is an input field that takes in the answer, a check answer button to submit the question, and a skip question button to see the answer immediately. The answer will be checked for null and non-integer values before the answer screen will be displayed. On the answer page, the correct answer will be displayed, and depending on whether the answer is correct or not different visual elements will be displayed. 

After answering all questions correctly a certain number of times, which depends on the difficulty (if question difficulty is equal to the number of times that question was answered correctly consecutively, then that question is "done"), the ending screen will be reached. 

On the question and answer pages, there is a restart button that takes the user back to the starting screen. 

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
