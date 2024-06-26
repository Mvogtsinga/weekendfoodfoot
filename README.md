![logowwf](https://github.com/Mvogtsinga/weekendfoodfoot/assets/152321059/0afe3128-79f2-43a7-9e0c-38750440edb7)


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
## Overview

I started this project alongside GitHub Projects with intention of planning and tracking the workflow to manage the expected workload. After setting out the epics for my project I broke them down into a set of user stories and smaller tasks, to help me monitor my progress and finish the website in time. Outside of user stories I also included a separate issues for creating each module of this README file, as I simply found it more motivating this way. To see the project's Kanban page please click [here](https://github.com/users/TulaUnogi/projects/3/views/1).

## User Stories

Initial stage of the project included stepping into the shoes of the future User. I thought about the features and functionality I would expect from the first use of the website and based on that I created a set of 12 User Stories. I labelled 10 of them as mandatory, as they provide the core functionality and source of important informations for the User. The remaining 2 Stories are labelled as NINTH- Nice To Have, Not Important, as they provide some improvements, but are not necessary for the User to enjoy the website's base functionality. 

The User Stories include the acceptance criteria and are broken down into smaller, bite- size tasks that I would tick on completion, so I could easily track my progress. During the coding session I would record the encountered bugs, issues and solutions related to the Story in the comments below. Once all of the tasks in the Issue are completed I would move the User Story form "In progress" to "Completed" card im my project's Kanban.

> List of Mandatory User Stories

1. [USER STORY: DEPLOYMENT](https://github.com/TulaUnogi/cat-beans-cafe/issues/16)
2. [USER STORY: ADMIN PANEL](https://github.com/TulaUnogi/cat-beans-cafe/issues/17)
3. [USER STORY: CREATE AN ACCOUNT](https://github.com/TulaUnogi/cat-beans-cafe/issues/18)
4. [USER STORY: EDITING PROFILE](https://github.com/TulaUnogi/cat-beans-cafe/issues/22)
5. [USER STORY: DELETING PROFILE](https://github.com/TulaUnogi/cat-beans-cafe/issues/23)
6. [USER STORY: TABLE BOOKING](https://github.com/TulaUnogi/cat-beans-cafe/issues/21)
7. [USER STORY: NAVBAR AND FOOTER](https://github.com/TulaUnogi/cat-beans-cafe/issues/20)
8. [USER STORY: ABOUT US](https://github.com/TulaUnogi/cat-beans-cafe/issues/19)
9. [USER STORY: MENU](https://github.com/TulaUnogi/cat-beans-cafe/issues/26)
10. [USER STORY: GOOGLE MAPS](https://github.com/TulaUnogi/cat-beans-cafe/issues/25)

> NINTH: Not Important, Nice To Have

11. [USER STORY: CAT CAROUSEL](https://github.com/TulaUnogi/cat-beans-cafe/issues/24)
12. [USER STORY: BOOKING CANCELLATION](https://github.com/TulaUnogi/cat-beans-cafe/issues/27)

##### [ Back to table of contents ](#table-of-contents)


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

##### [ Back to table of contents ](#table-of-contents)

# feature left to implement

Features Left to Implement

- [USER STORY: BOOKING CANCELLATION] (https://wff-ba2fd89f325f.herokuapp.com/account/) - As I've mentioned the initial version of this model is left for now since customer can currently fully delete their booking. 

##### [ Back to table of contents ](#table-of-contents)

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

##### [ Back to table of contents ](#table-of-contents)



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
| User can delete profile     |Pass|
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


##### [ Back to table of contents ](#table-of-contents)

---
 
# Known bugs 

- I observed one blue submit button- it is automatically generated by crispy forms and somehow the form settings did not applied to this button. It's a small bug of low priority for me at the current stage.
- There's small image clipping during the cat carousel transitions on smaller screens.
- No error message displaying when passing wrong login details
- The function that was supposed to prevent booking dates in the past is currently preventing nothing, unfortunately... You may be brave and try to trick the system into timetravelling, but Admin will always see what day the booking was made on anyway and won't accept such a silly tricks!


##### [ Back to table of contents ](#table-of-contents)

# Bugs
No current bugs in the project.

But some  bugs occurred during the development of the project such as:
Deploying the project to Heroku. This was solved by creating a new app.


# Deployment

Heroku was the main deployements Tools for this project. I add a Procfile and requirements.txt files to the project.

A new app was set up in Heroku and the config vars were added to the app.

GitHub was selected as the deployment menthod and the GitHub repository was linked to Heroku.

"Deploy Branch" was selected to manually deploy the project.

# Deployment

#### The deployment stage of the website should follow the steps below:

> Create the Heroku app

- Sign up / Log in to Heroku
- In Heroku Dashboard page select 'New' and then 'Create New App'
- Name a project - I decided on the Cat Beans Café (the app's name must be unique)
- Select EU as that was my region in the moment of creating the app
- Select "Create App"
- In the "Deploy" tab choose GitHub as the deployment method
- Connect your GitHub account/ find and connect your GitHub repository

> Set up enviroment variables

- In the Django app editor create env.py in the top level
- In env.py import os
- In env.py set up necessary enviroment variables:
  - add a secret key using: os.environ['SECRET_KEY'] = 'your secret key'
  - for the database variable the line should include os.environ['DATABASE_URL']= 'Paste the database link in here'
  - in settings.py replace value of SECRET_KEY variable with os.environ.get('SECRET_KEY')
  - in settings.py change the value of DATABASES variable to 'default': dj_database_url.parse(os.environ.get("DATABASE_URL"))
- In Django app's settings.py on top of the file add:
```
from pathlib import Path
import os
import dj_database_url
if os.path.isfile('env.py'):
    import env
```
- Navigate to the "Settings" tab in Heroku.
- Open the "Config Vars" section and add DATABASE_URL as Key and the database link from app's env.py as Value
- Add SECRET_KEY for the Key value and the secret key value from env.py as the Value
- In the terminal migrate the models over to the new database connection
- In settings.py add the STATIC files settings as follows:
```
STATIC_URL = '/static/'
STATICFILES_DIRS = [os.path.join(BASE_DIR, 'static')]
STATIC_ROOT = os.path.join(BASE_DIR, "staticfiles")
```
- Change the templates directory in settings.py to: TEMPLARES_DIR = os.path.join(BASE_DIR, 'templates')
- In TEMPLATES variable change the 'DIRS' key to look like this: 'DIRS': [TEMPLARES_DIR],
- Add Heroku to the ALLOWED_HOSTS list (the format will be your-app-name.herokuapp.com, you can copy it from the Domains section in Settings tab in your Heroku app)
- If you haven't done that up to this point, then create in your Django app's code editor new top level folders: static and templates
- Create a new file on the top level directory - Procfile, remembering to use a capital letter
- Within the Procfile add following:
```
web: guincorn PROJECT_NAME.wsgi
``` 
- In the terminal, add the changed files, commit and push to GitHub

> Heroku deployment

- In Heroku, navigate to the Deployment tab and deploy the branch manually 
- Heroku will display a build log- watch the build logs for any errors
- Once the build process is completed Heroku displays 'Your App Was Successfully Deployed' message and a link to the app to visit the live site
- As my first 2 build attempts failed I needed to apply changes to my code (I forgot to set up the static files and templates) to successfully deploy on the 3rd time 

#### Forking the repository

By forking the GitHub Repository you can make a copy of the original repository to view or change without it effecting the original repository. You can do this with following steps:

- Log in to GitHub or create an account
- Enter this [repository link](https://github.com/TulaUnogi/cat-beans-cafe)
- Select "Fork" from the top of the repository
- A copy of the repository should now be created in your own repository

#### Create a clone of this repository

Creating a clone enables you to make a copy of the current version of this repository to run the project locally. To do this follow steps below:

- Navigate to https://github.com/TulaUnogi/cat-beans-cafe
- Click on the <>Code button at the top of the list of files
- Select the "HTTPS" option on the "Local" tab and copy the URL it provides to the clipboard
- Navigate to your code editor and in the terminal change the directory to your chosen location 
- Type "git clone" and paste the GitHub repository's link
- Press enter and git will clone the repository for you

##### [ Back to table of contents](#table-of-contents)

# resources

-  [Code Institute Full Stack Development course materials](https://codeinstitute.net/global/full-stack-software-development-diploma/?sitelink=FullStackDiploma-IRL&utm_term=code+institute&utm_campaign=CI+-+IRL+-+Search+-+Brand&utm_source=adwords&utm_medium=ppc&hsa_acc=8983321581&hsa_cam=14304747355&hsa_grp=128775288209&hsa_ad=635725005315&hsa_src=g&hsa_tgt=kwd-319867646331&hsa_kw=code+institute&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=Cj0KCQiAgqGrBhDtARIsAM5s0_l13h8fkiqZeHnw16zshbX6svuL8YJNrw6G-RFdq03RQybQXLSoZiYaAjGqEALw_wcB) 
- [Django documentation](https://www.djangoproject.com/)
- [Crispy forms docs](https://django-crispy-forms.readthedocs.io/en/latest/)
- [Bootstrap docs](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
- [Stack overflow](https://stackoverflow.com/)
- [Slack](https://slack.com/intl/en-ie/)
- [Create Django project]( https://www.geeksforgeeks.org/how-to-create-a-django-project/)
- [Heroku_Deployment]{https://devcenter.heroku.com/articles/github-integration#:~:text=You%20can%20configure%20GitHub%20integration,to%20configure%20automatic%20GitHub%20deploys.}
  
##### [ Back to table of contents ](#table-of-contents)



# Credits and acknowledgements

## Credits

- Images : Unsplash
- templates: code institute
  
  > Pictures

- [Mid-coated Brown Cat](https://www.pexels.com/photo/mid-coated-brown-cat-982865/) by <b>Alena Koval</b> on Pexels
- [Cat at the table](https://unsplash.com/photos/black-cat-on-white-table-ZxChxgJa6X0) by <b>Madalyn Cox</b> on Unsplash
- [Cup of coffee](https://pixabay.com/photos/tea-cat-coffee-coffee-shop-cup-2343391/) by <b>yukiqwa</b> on Pixabay
- [Black Steel Welcome Hanging Signage](https://www.pexels.com/photo/black-steel-welcome-hanging-signage-1406282/) by <b>Henry & Co.</b> on Pexels
- [Menu background](https://pixabay.com/photos/coffee-mug-heart-caffeine-food-5176961/) by <b>Konrad Janik</b> on Pixabay

- Cat carousel pictures:
  1. [Fluffy black cat](https://pixabay.com/photos/couch-cat-pet-feline-animal-6654015/) by <b>Spike Summers</b> on Pixabay 
  2. [Calico cat](https://www.pexels.com/photo/calico-cat-1359300/) by <b>Cats Coming</b> on Pexels
  3. [Orange tabby cat](https://www.pexels.com/photo/adorable-animal-cat-close-up-208930/) by <b>Pixabay</b> on Pexels
  4. [Cat with a mouse toy](https://www.pexels.com/photo/cat-with-a-mouse-toy-3216568/) by <b>lil artsy</b> on Pexels
  5. [Two cosy tabby cats](https://www.pexels.com/photo/two-tabby-kittens-lying-down-1787414/) by <b>Cats Comin</b> on Pexels
  6. [Little kitten](https://www.pexels.com/photo/close-up-photo-of-orange-tabby-cat-2581153/) by <b>samer daboul</b> on Pexels
  7. [Christmas kitten](https://www.pexels.com/photo/close-up-photography-of-white-cat-besides-christmas-lights-735423/) by <b>Eftodii Aurelia</b> on Pexels


## Acknowledgements

- I would like to thank my Code Institute mentor for their support throughout the development of this project.
- I would like to thank the Code Institute Slack community for the moral support; it kept me going during periods of self doubt and imposter syndrome.
- I would like to thank my family, for believing in me, and allowing me to make this transition into software development.
- I would like to thank the Bootcamp crew, for supporting me in my career development change towards becoming a software developer.



![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

##### [ Back to table of contents ](#table-of-contents)






