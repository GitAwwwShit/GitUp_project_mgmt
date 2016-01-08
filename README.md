# Galvanize Group Project Proposal

## Group Members
- Eric Boone
- Anna Huffman
- Eli Parkhurst
- Brian Huber

## Project Description
GitUp is an app designed to track the activity of children in order to encourage healthy lifestyle choices. The app charts the activity level of the user over time and rewards the user with badges for achieving certain goals.

**Stretch** We would like to have both child and parent users. Parent users can set goals and rewards for children to reach and track multiple children at once. Child users can see their progress on reaching the goals set by the parents.

**Super Stretch** The app can take in input from fitbit and other devices to use in the app.

## Who uses it?
- Parents of kids
- Kids (ages 2 to 12ish)

## What outputs do they need?
####MVP
* minutes active/outside
* Status/progress of goals
* activities completed
* logged in/out

#### Stretch
- progress vs norm/recomendations
- badges/achievments
- Rewards available/earned
- frequency on app
- share on social media
- progress vs freind group

## What inputs are needed to generate those outputs?
####MVP
* Activity input
* user login/logout
* Amount of time input
* type of activity

####Stretch
- multiple kids
- personal goals
- create friend groups

## What technologies do you plan to use?
- Express
- Passport
- AJAX
- Postgres
- bootstrap-customized
- node
- knex
- yeoman
- postman

## Feature list

###Landing page:

#####MVP
- The visitor will see marketing language, images, and branding
- The visitor will see login button

#####Stretch
- The visitor will see success stories
- The visitor will be able to downloadable documents to recommended activities and time lengths
- The visitor will see overall user stats

###Login Page

#####MVP
- The user will be able to login with social auth with google and facebook

#####Stretch
- The user will be directed to a "how to page" on the first login

###Inputs Page

#####MVP
- User can create an activity and how long it was performed
- User can create goals
- User can edit goals
- User can remove old goals

#####Stretch
- User can create rewards in database
  - Rewards can be directly linked to an activity
  - Rewards can be traded with a currency that is earned through the activity
- User can create another kid in the app
- User can add friends to create a group

###Dashboard Page

#####MVP
- The user can view the minutes that their child was active/outside
- The user can view the status/progress of goals
- The user can view activities completed
- The user can view if they are logged in and logout

#####Stretch
- The user can see the data visualized and compare it to their group or average of the site
- The user can see badges/rewards earned
- the user can see upcoming goals/rewards
