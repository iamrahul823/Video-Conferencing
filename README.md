#   Video Conferencing Web App


Video conferencing solutions with `Unite`
using peer-to-peer connection.

<p align="center">

<img src="https://user-images.githubusercontent.com/59837325/125489372-57d3ad66-fb25-40f8-8d54-5514cbe4b648.png" alt="Unite-logo"/>
</a>
</p>



## Features and Interfaces

1. Landing Page and Feeback Form
   - Seamless landing page with `Login with Google` button for user Login using Firebase Authentication 

 
   - One of the most important part of Agile is feedback, therefore the app has a feedback form in the footer 
  
   
   - Witness by journey of these 4 weeks, through a concise timeline on my landing page
   

2. Home page 
   - Has a signout button with app cards for different features and left division shows the rooms created by user as well as recent rooms visited
   
   
   - Toggle between dark-light using the moon icon, according to your preference
   
   
   - Preview app cards for the application
 
   
3. Create Meeting
   - Create a room and invite people to join by copying the meeting code

   - Enter the common chat room that **persist the messages** using MongoDB 

4. Join Meeting
   - Enter the copied meeting ID in a form and join the room with your loved ones. 

5. Video calling & Persistent text chat
   - Chat with your friends, family and professional peers before, during and after the meeting. 
   
   - Screen Share options


6. Schedule Meeting 
   - Schedule Meeting with Google Calendar and invite people by just entering their email addresses and the app schedules a meet for you with a unique meeting ID as well!

   - Mail sent on scheduling a meeting

7. AI powered posture bot
   - Using `Tf.js` posenet model, the bot notifies the user if they are sitting in a bad posture or too close to the screen. 
   - Keep your health in check and use this functionality with and without even being in a meeting

## Tech stack

![image](https://user-images.githubusercontent.com/59837325/125461960-da7d575b-b1e8-43f4-ae22-6f3403df44d1.png)

### Tools and Languages: 
<p align="left"> <a href="https://getbootstrap.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://cloud.google.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://heroku.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://sass-lang.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="sass" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>

## Points to remember while testing the app

1. Allow **permissions** for camera and mic
2. In case any **user is not broadcasted** it is probably due to server overload, **REFRESH** the window to solve this. 
3. Make sure the **URL** is starting with https
4. While **scheduling a meet** make sure the start and end date follow a logical sequence or else it’ll show an error. 
5. While testing the **Posture** bot, allow permissions for the camera and allow **notifications**, and **REFRESH** the page for changes to take effect. 
6. Wait for the model to analyze, and check for **notifications** 

## Instructions


1. `git clone https://github.com/iamrahul823/Video-Conferencing.git` 
2. `cd ./Video-Conferencing`
3. Install node dependencies 
   - `npm install`
4. Replace firebase API keys with your configurations
5. Create a `.env` file 
   - Add relevant credentials
   - `cp .env.example .env` 
5. `npm run dev`
6. The app is now running at http://localhost:3030/landing 


## Useful Links



## Need help?

Feel free to contact me on [LinkedIn](https://www.linkedin.com/in/rahul-596280226/) 

[![Instagram](https://img.shields.io/badge/Instagram-follow-purple.svg?logo=instagram&logoColor=white)](https://www.instagram.com/mikuchettri/) [![Twitter](https://img.shields.io/badge/Twitter-follow-blue.svg?logo=twitter&logoColor=white)](https://twitter.com/Rahul99839761) [![Medium](https://img.shields.io/badge/Medium-follow-black.svg?logo=medium&logoColor=white)]()

---------

```javascript

if (youEnjoyed) {
    starThisRepository();
}

```

-----------

# Video-Conferencing
