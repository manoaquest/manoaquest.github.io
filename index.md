# ManoaQuest

## No More Boring Classes

No matter if you’re a professor or a student coursework can feel like a drag. Students struggle with motivation while professors try to keep the material engaging. ManoaQuest is one possible solution.

ManoaQuest gamifies courses at UH Manoa. When a professor integrates ManoaQuest into a course it doesn’t require any changes in scheduling. Rather ManoaQuest turns homework assignments into quest with rewards upon completion. Students can track their progress and compete with other students on the leaderboard.

These small features motivates students through rewards and competition. It keeps students engaged at the cost of a small time investment from the professor. The end goal of ManoaQuest is to boost the overall grades of students in a positive and engaging way.

## ManoaQuest Features

* A robust questing system:
  * The professor can create quest whether it’s studying with a partner or turning in assignments.   

* Personal avatar:
  * Your avatar represents you in ManoaQuest. Earn rewards and gold to purchase customizations.

* Leaderboard:
  * Students can feel competitive. Getting a high score on a quiz can push your avatar up the rankings.

* Notifications:
  * ManoaQuest will send an email with reminders about quest before they expire.

## [Site Walkthrough](http://manoaquest.meteorapp.com/)

When first accessing the site the user is presented with this landing page. It contains a simple login form and basic information.

![Image](/screenshots/landing-page.png)

![Image](/screenshots/cas.png)

After signing in, the user is presented with one of several different home pages depending on their role in the class.

![Image](/screenshots/unauthorized.png)

If one is not a UHM user, they would not be allowed to any of the sites.

If the user who logged in was a student, their home page would look similar to this:

![Image](/screenshots/student-home-page-1.png)
![Image](/screenshots/student-home-page-2.png)

A student will be able to see their, avatar name, their real name, and their current gold along with other relevant information. They would also be able to change their avatar based on url! Super cool!

Below the header of the content is a list of currently available quests that are eligible to request for completion and a list of quests that have been completed.

![Image](/screenshots/approve-quest.png)

Professors will be able to create quests.

![Image](/screenshots/create-quest.png)

![Image](/screenshots/quest-created.png)

Professors will be able to edit the quests.

![Image](/screenshots/edit-quest.png)

Professors will also be able to update the quests.

![Image](/screenshots/quest-updated.png)

Professors will be able to approved submitted quest to rewards. More importantly professors will be able to create quest.

![Image](/screenshots/teacher-page.png)

Teacher assistants will be able to also approve submitted quest. This is to help the professor keep up with approvals.

![Image](/screenshots/error-404.png)

Users will also be redirected if they are on an incorrect site

## Developers Guide

* To run this application, you must first have [Meteor](https://www.meteor.com/) must be installed on your machine. 
* Fork this project on https://github.com/manoaquest/Manoa-Quest
* Clone the project to your machine with:
```
git clone https://github.com/manoaquest/Manoa-Quest.git
```
* cd into the app/ directory and install libraries with:
```
meteor npm install
```
* Run the application with:
```
meteor npm run start
```
* Open the site on localhost:3000 from any browser. If you have an UHM account, you can login. 

## Initial User Study
We surveyed past members of the UHM community by directing them to our sites and allowing them to do whatever their hearts desired.
- Lisa Zhou
- Sheena Galutira
- Nikki Kobayashi
- Javen Nakamoto
- Adam Akamine

Feedback:
- Interesting, wish there was a guide!
- I wish I had this when I was in school!
- Wow, such wow.
- I don't even like RPG's, but this was interesting!
- Can I make my own characters?
- Seems a little buggy...
- Very interesting spin on this, school would've been much more competitive if we had this

## Development History
## Milestone 1 - Mockup and Deployment: 
Our first project milestone set goals to create HTML mockup pages for our webapp in Meteor. Additionally since we created the webapp in Meteor, we also set out to link all the pages together using FlowRouter. The last goal is to deploy our app to Galaxy so that we can have a live version to test with.

[GitHub Project - Milestone 1](https://github.com/manoaquest/ManoaQuest/projects/1)

Our goals in this milestone was managed by GitHub's project manager feature with each goal implemented as a card that we could move between a backlog, in progress, and finished. 

![Image](/screenshots/m1screencap.PNG)

Each group member worked in their own branch and then merged into the master branch when we all completed our work.

![Image](/screenshots/m1network.PNG)

## Milestone 2 - Mockup and Deployment: 
For this milestone, we decided to jump ahead and connect the database to every page that needed a database. We also were able to route the pages through the students id's. 

[GitHub Project - Milestone 2](https://github.com/manoaquest/Manoa-Quest/projects/1)

Our goals in this milestone was managed by GitHub's project manager feature with each goal implemented as a card that we could move between a backlog, in progress, and finished. 

![Image](/screenshots/m2screencap.png)

Each group member worked in their own branch and then merged into the master branch when we all completed our work.

![Image](/screenshots/m2network.png)

## Milestone 3 - Let's Finish this!: 
For this milestone, we realized that we got a lot done during the last milestone, so we would ensure we reached our MVP before the deadline which included a LOT more!

- Ensure all pages are connected
- Ensure database setup is perfect
- Correct routing based on user login
- 404, Unauthorized page creation
- Uniform styling!
- Custom sprites!

[GitHub Project - Milestone 3](https://github.com/manoaquest/Manoa-Quest/projects/1)

Our goals in this milestone was managed by GitHub's project manager feature with each goal implemented as a card that we could move between a backlog, in progress, and finished. 

![Image](/screenshots/m3screencap.png)

Each group member worked in their own branch and then merged into the master branch when we all completed our work.

![Image](/screenshots/m3network.png)
