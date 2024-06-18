<img src="![logowwf](https://github.com/Mvogtsinga/weekendfoodfoot/assets/152321059/0afe3128-79f2-43a7-9e0c-38750440edb7)
"widht="200" height="200">


# Welcome to WEEKENDFOODFOOT Restaurant <br>
### A restaurant website <br>

A responsive,restaurant website with registration and table booking system with different formats for customers.create as a final Project Portfolio during the Full stack Software Developer-Skills Bootcamp at Code Institute.
[Link to the live site here](https://wff-ba2fd89f325f.herokuapp.com/)

-By Aubin KOENIGSSOHN-

## Table of contents 

 1. [ UX ](#ux)
 2. [ Agile Development ](#agile-development)
 3. [ Features implemented ](#features-implemented)  
 4. [ Features Left to Implement ](#features-left-to-implement)  
 5. [ Technology used ](#technology-used) 
 6. [ Testing ](#testing)  
 7. [ Bugs ](#known-bugs)  
 8. [ Deployment](#deployment)
 9. [ Resources ](#resources)  
 10. [ Credits and acknowledgements ](#credits-and-acknowledgements)


# UX
## Database planning 
<img src="![IMG-20240325-WA0030](https://github.com/Mvogtsinga/weekendfoodfoot/assets/152321059/38c54b06-f9d6-456d-b70a-154f4c40fab0)"widht="25px" height="25px">


## UX design


## Overview
## Design
Initial design planing
The first design of this project was to choice and appeling picture for the homepage and login features prototypes.
<img src="![home wff](https://github.com/Mvogtsinga/weekendfoodfoot/assets/152321059/d74240f8-4a5d-4364-b24d-fd2b182d3c6e)"widht="200px" height="200px">

<img src="![userlogin wff](https://github.com/Mvogtsinga/weekendfoodfoot/assets/152321059/8491c30e-b6b0-4453-a31b-d654bcfa7ac2)" "widht="200px" height="200px">

<img src="![signup wff](https://github.com/Mvogtsinga/weekendfoodfoot/assets/152321059/0ef76d89-4f78-4716-bd44-3f61507c8e02)" "widht="150px" "height="150px">

<img src="![reservation wff](https://github.com/Mvogtsinga/weekendfoodfoot/assets/152321059/b9f69e95-6988-4c44-b204-7e90d4b4f884)" "widht="150px" "height="100px">

<img src="![menu wff](https://github.com/Mvogtsinga/weekendfoodfoot/assets/152321059/aaf7196f-a355-4eea-adc7-ba78e2ba61f6)" "widht="150px" "height="100px">




My first preoccupation was to build a direct connection with a potential user. To attempt my goal I chose a mixture of Burger and hell color. 

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

## Wireframes
The next stage of UX design planning was the basic wireframes using Basalmiq. I wanted to create a pleasing and easy to navigate website for the potential user. 


# Agile Development

# features-implemented

### Navbar and Footer:

- Navbar and footer are present on every page
- Navbar's content changes depending on user authentication, allowing access to profile and user bookings
- Footer includes café's opening times, social links and address to provide the necessary informations in an easy way.

### Index page:

- The homepage provides the links to booking and about us page.
- It can be accessed without signing in.

### About Us page:

- Main page includes a short information about the café and set of 4 cards with pictures and description.
- Each of the card includes the button, that triggers a fullscreen modal.
- The modals contain informations about the menu, contact details with embedded google maps, link to booking page and gallery with cat pictures (cat carousel).
- About Us page can be accessed without signing in.

### Authentication and profile management:

- User can sign up to create their profile 
- User can log in to their account and update their informations
- User can delete their account alltogether with all their data
- The authentication process is safe thanks to [Django-AllAuth](https://github.com/pennersr/django-allauth) and csrf tokens.

### Bookings:

- User can pass their data to create a booking.
- User can edit their selected booking.
- Currently the initial version of booking cancellation view has not been fully implemented. I decided to implement an automatic delete_booking view, that allows User to quickly remove their booking from the system.

### Responsiveness:

- Website is responsive thanks to Bootstrap and media queries applied.
- There's a hamburger navbar on small devices.

##### [ Back to Top ](#table-of-contents)

# feature left to implement

Features Left to Implement

- [USER STORY: BOOKING CANCELLATION] (https://wff-ba2fd89f325f.herokuapp.com/account/) - As I've mentioned the initial version of this model is left for now since customer can currently fully delete their booking. 

##### [ Back to Top ](#table-of-contents)

# Technology used 

The site has been built with the following tech and tools:

- Html - for page structure
- CSS - for custom styling
- Python - for the backend
- Javascript - for timeout in messages
- Django - framework used to build this project
- Jinja - templating language rendering logic within html documents
- Bootstrap 5 - front end framework used by me alongside Django, helps with fast and efficient styling
- Heroku PostgreSQL - used as the database
- Font Awesome - for social media icons
- Google Fonts- currently only for the hero image font
- GitHub - for storing the code and for the projects Kanban
- Heroku - for hosting and deployement of this project
- Cloudinary - hosting the static files 
- Git - version control tool

##### [ Back to Top ](#table-of-contents)



# Testing

### Responsiveness

I was testing for responsiveness on an Ideapad laptop and a Samsung Galaxy A5 using the most up to date versions of Google Chrome, Mozilla Firefox and Opera versions. For more detailed testing I was using Google DevTools.

> Index page:

![Index page](static/images/readme-images/responsive-index.png)


> About Us page:

![Index page](static/images/readme-images/responsive-about.png)


> Sign Up page:

![Index page](static/images/readme-images/responsive-signup.png)


> Sign In page:

![Index page](static/images/readme-images/responsive-sign-in.png)



### Manual testing

#### Account Registration Tests
| Test |Result  |
|--|--|
| User can create profile | Pass |
| User can log into profile | Pass |
| User can log out of profile | Pass |
| Messages are displaying | Pass |
| Messages are dismissable by button and timeout | Pass |



---

#### User Navigation Tests

| Test | Result  |
|--|--|
| User can easily navigate to Bookings | Pass |
| User can access About Us page| Pass|
| User access their account page|Pass|
| User can access the card content in About Us|Pass|
| SuperUser can access admin page|Pass|



---

#### Account Authorisation Tests

| Test | Result  |
|--|--|
| Only Superuser can access admin page |Pass|
| Non authorised user book a table | Pass |
| Non authorised user won't access profile page| Pass|



---

#### Booking and Profile Tests

| Test |Result  |
|--|--|
|User can make a booking | Pass |
|User can view all of their bookings | Pass |
|User can delete their booking | Pass |
|User can edit booking | Pass |
|User can make more than one booking | Pass |
|User can delete their account | Pass |
|User can edit their information | Pass |
|User can see the confirmation information | Pass |



---

#### Admin Tests

| Test |Result  |
|--|--|
|Items display correctly on front-end when updated / added |Pass|
|Admin can confirm or decline bookings |Pass|


##### [ Back to Top ](#table-of-contents)

---
 
# Known bugs 

- I observed one blue submit button- it is automatically generated by crispy forms and somehow the form settings did not applied to this button. It's a small bug of low priority for me at the current stage.
- There's small image clipping during the cat carousel transitions on smaller screens.
- No error message displaying when passing wrong login details
- The function that was supposed to prevent booking dates in the past is currently preventing nothing, unfortunately... You may be brave and try to trick the system into timetravelling, but Admin will always see what day the booking was made on anyway and won't accept such a silly tricks!


##### [ Back to Top ](#table-of-contents)

# Bugs
No current bugs in the project.

But some  bugs occurred during the development of the project such as:
Deploying the project to Heroku. This was solved by creating a new app.


# Deployment

Heroku was the main deployements Tools for this project. I add a Procfile and requirements.txt files to the project.

A new app was set up in Heroku and the config vars were added to the app.

GitHub was selected as the deployment menthod and the GitHub repository was linked to Heroku.

"Deploy Branch" was selected to manually deploy the project.

# resources

-  [Code Institute Full Stack Development course materials](https://codeinstitute.net/global/full-stack-software-development-diploma/?sitelink=FullStackDiploma-IRL&utm_term=code+institute&utm_campaign=CI+-+IRL+-+Search+-+Brand&utm_source=adwords&utm_medium=ppc&hsa_acc=8983321581&hsa_cam=14304747355&hsa_grp=128775288209&hsa_ad=635725005315&hsa_src=g&hsa_tgt=kwd-319867646331&hsa_kw=code+institute&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=Cj0KCQiAgqGrBhDtARIsAM5s0_l13h8fkiqZeHnw16zshbX6svuL8YJNrw6G-RFdq03RQybQXLSoZiYaAjGqEALw_wcB) 
- [Django documentation](https://www.djangoproject.com/)
- [Crispy forms docs](https://django-crispy-forms.readthedocs.io/en/latest/)
- [Bootstrap docs](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
- [Stack overflow](https://stackoverflow.com/)
- [Slack](https://slack.com/intl/en-ie/)
  
##### [ Back to Top ](#table-of-contents)



# Credits and acknowledgements

## Credits

- Images : Unsplash
- templates: code institute
- 

## Acknowledgements

- I would like to thank my Code Institute mentor for their support throughout the development of this project.
- I would like to thank the Code Institute Slack community for the moral support; it kept me going during periods of self doubt and imposter syndrome.
- I would like to thank my family, for believing in me, and allowing me to make this transition into software development.
- I would like to thank the Bootcamp crew, for supporting me in my career development change towards becoming a software developer.



![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)







