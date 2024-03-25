<img src="![IMG-20240325-WA0025](https://github.com/Mvogtsinga/weekendfoodfoot/assets/152321059/f4114137-9f45-45ca-b59a-091b84f4c33f)"widht="65px" height="50px">


Welcome to WEEKENDFOODFOOT Restaurant <br>
A restaurant website <br>

A responsive,restaurant website with registration and table booking system with different formats for customers.create as a final Project Portfolio during the Full stack Software Developer-Skills Bootcamp at Code Institute.
[Link to the live site here](https://wff-ba2fd89f325f.herokuapp.com/)

-By Aubin KOENIGSSOHN-

# Table of contents
<ol>
  <li>UX</li>
  <li>Agile Development </li>
  <li>Features implemented </li>
  <li>Features Left to implement </li>
  <li>Technology used</li>
  <li>Testing</li>
  <li>Bugs</li>
  <li>Deployment</li>
  <li>Resources</li>
  <li>Credits and acknowledgements </li>
</ol>

# UX
# Database planning 
## Data structure
## Data models
### UserProfile model
### Bookings model

# UX design
# Overview
## Design
Initial design planing
The first design of this project was to choice and appeling picture for the homepage and login features prototypes.
<img src="![home wff](https://github.com/Mvogtsinga/weekendfoodfoot/assets/152321059/d74240f8-4a5d-4364-b24d-fd2b182d3c6e)"widht="200px" height="200px">

<img src="![userlogin wff](https://github.com/Mvogtsinga/weekendfoodfoot/assets/152321059/8491c30e-b6b0-4453-a31b-d654bcfa7ac2)" "widht="200px" height="200px">

My first preoccupation was to build a direct connection with a potential user. To attempt my goal I chose a mixture of Burger and 

Site User
- Someone or a group of people over 18 from the sport's area
- A sport's team looking for a place to eat after the weekend's games
- People who prefers to arrange their bookings digitally to secure a place

Goals for the website
- To allow customers to see the menu before visiting the restaurant
- to allow customers to plan their booking in advance
- To safely store the bookings data and make it available for staff.
- To allow customers to view in advance the table availability
- To safely manage the food logistic

# Wireframes
The next stage of UX design planning was the basic wireframes using Basalmiq. I wanted to create a pleasing and easy to navigate website for the potential user. 


# Agile Development

## Overview

# Features implemented

# Features Left to implement



# Technology used
The site has been built with the following tech and tools:
<ol>
  <li>HTML5</li>
  <li>CSS</li>
  <li>Python</li>
  <li>Django - database framework</li>
  <li>ElephantSQL - database hosting</li>
  <li>Cloudinary - media hosting</li>
  <li>Bootstrap 5</li>
  <li>GitHub Repo - code storage</li>
  <li>Git - version control</li>
  <li>GitPod & VS Code - IDE</li>
  <li>Heroku - live site hosting</li>
</ol>


# Testing

# Bugs
No current bugs in the project.

But some  bugs occurred during the development of the project such as:
Deploying the project to Heroku. This was solved by creating a new app.


There was an issue with trying to get the dropdown menu to work. By mistake I hadn't put the link to the JavaScript file in the html file. After I added the link, the dropdown menu worked but was only showing the dropdown part while it was being pressed. Also the words were not visible and the width of the dropdown was very narrow and that's probably why the words weren't on it. I solved the issue by changing the css.

The header was set to position: fixed and was covering the content. To solve this I increased the size of the margin at the top of the main section.

I had problems deploying my project to Heroku. This was solved by adding the correct Config Vars to Heroku.

The navigation menu was showing the same things for signed in users as signed out users. This was solved by changing the urls.

The text on the buttons was not fitting on the buttons in the mobile view so I set the font size in percentage instead of pixels.

I was trying to prevent double bookings by filtering out appointments that had been booked. It wasn't working and the booked appointments were still showing up on the list of available appointments. This was solved by editing the booking view.

# Deployment

Heroku was the main deployements Tools for this project. I add a Procfile and requirements.txt files to the project.

A new app was set up in Heroku and the config vars were added to the app.

GitHub was selected as the deployment menthod and the GitHub repository was linked to Heroku.

"Deploy Branch" was selected to manually deploy the project.

# Resources

# Credits and acknowledgements

- I would like to thank my Code Institute mentor for their support throughout the development of this project.
- I would like to thank the Code Institute Slack community for the moral support; it kept me going during periods of self doubt and imposter syndrome.
- I would like to thank my family, for believing in me, and allowing me to make this transition into software development.
- I would like to thank the Bootcamp crew, for supporting me in my career development change towards becoming a software developer.



![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)







