# model-view-controller-mytechblog

Module 14 Challenge Assignment: Model-View-Controller (MVC) Challenge: Tech Blog

Deployed Link: https://module14-blog.herokuapp.com 


## Badges
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Table of Contents
  * [License](#license)
  * [Description](#description)
  * [User Story](#user-story)
  * [Acceptance Criteria](#user-story)
  * [Installation](#installation)
  * [Setup](#setup)
  * [Usage](#usage)
  * [Screenshots of Application in Use](#screenshots-of-application-in-use)
  * [Technologies](#technologies)
  * [How to Contribute](#how-to-contribute)
  * [Tests](#tests)
  * [Questions?](#questions)


## License
  Read more about MIT here:
  [MIT](https://opensource.org/licenses/MIT)


## Description
  This is a full-stack CMS-style blog site where users can publish posts and comment on other users' blog posts. With login authentication, logged-in users have access to the dashboard where they can also edit or delete their posts and or comments. Additionallly, this application is MVC structured and makes use of multiple packages such as handlebars, bcrypt, express.sessions, sequelize and more to ensure the most optimized experience.


## User Story
    AS A developer who writes about tech
    I WANT a CMS-style blog site
    SO THAT I can publish articles, blog posts, and my thoughts and opinions


## Acceptance Criteria 
    GIVEN a CMS-style blog site
    WHEN I visit the site for the first time
    THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
    WHEN I click on the homepage option
    THEN I am taken to the homepage
    WHEN I click on any other links in the navigation
    THEN I am prompted to either sign up or sign in
    WHEN I choose to sign up
    THEN I am prompted to create a username and password
    WHEN I click on the sign-up button
    THEN my user credentials are saved and I am logged into the site
    WHEN I revisit the site at a later time and choose to sign in
    THEN I am prompted to enter my username and password
    WHEN I am signed in to the site
    THEN I see navigation links for the homepage, the dashboard, and the option to log out
    WHEN I click on the homepage option in the navigation
    THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
    WHEN I click on an existing blog post
    THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
    WHEN I enter a comment and click on the submit button while signed in
    THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
    WHEN I click on the dashboard option in the navigation
    THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
    WHEN I click on the button to add a new blog post
    THEN I am prompted to enter both a title and contents for my blog post
    WHEN I click on the button to create a new blog post
    THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
    WHEN I click on one of my existing posts in the dashboard
    THEN I am able to delete or update my post and taken back to an updated dashboard
    WHEN I click on the logout option in the navigation
    THEN I am signed out of the site
    WHEN I am idle on the site for more than a set time
    THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments


## Installation
  1. To install application, clone the main project via the HTTP or SSH link on github.

```
git clone
```

2. Once cloned, open up the project folder in your text editor and run the following command in terminal to install all dependencies.

```
npm install
```


## Setup
Create an '.env' file in the main directory path and include the following data:

```
DB_NAME='developing_tech_db'
DB_USER='root'
DB_PASSWORD=''
```

Once your '.env' has been created with the corresponding data, open up the schema ('db/schema.sql') and update the database label to match with the database you included in your '.env' file.


## Usage
  1. Run `node index.js` in terminal to start. 
  2. Follow through the prompts as required. 

  Note:

  - Need to be in the main folder in terminal when running the command.


## Screenshots of Application in Use

Home Page:
<img width="1108" alt="Screen Shot 2023-01-16 at 1 03 11 AM" src="https://user-images.githubusercontent.com/114618684/212617569-3dae7df0-768b-40fc-a043-5345e4f26c0d.png">

Login:
<img width="952" alt="Screen Shot 2023-01-16 at 12 56 22 AM" src="https://user-images.githubusercontent.com/114618684/212617532-76a25043-c57d-415b-98ca-4f665944c0a4.png">

Signup:
<img width="1093" alt="Screen Shot 2023-01-16 at 1 04 38 AM" src="https://user-images.githubusercontent.com/114618684/212617648-68505709-9e94-4b6c-8300-ba7fb571a936.png">


Create New Post:
<img width="1095" alt="Screen Shot 2023-01-16 at 12 59 57 AM" src="https://user-images.githubusercontent.com/114618684/212617554-c3539209-f06c-420e-ac8f-e319f6ff94b2.png">

Add a comment:
<img width="1096" alt="Screen Shot 2023-01-16 at 1 04 04 AM" src="https://user-images.githubusercontent.com/114618684/212617612-08a3aebf-b236-47a4-b659-800938ae9665.png">



## Technologies
* [Node.js](https://nodejs.org/en/)
* [Express.js](https://expressjs.com)
* [Handlebars Template Engine](https://handlebarsjs.com)
* [Bcrypt](https://www.npmjs.com/package/bcrypt)
* [Sequelize](https://sequelize.org)
* [Dotenv](https://www.npmjs.com/package/dotenv)
* [Heroku](https://devcenter.heroku.com/start)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)


  ## How to Contribute
  [Contributor Covenant](https://www.contributor-covenant.org/)  


  ## Questions?
  ### Reach me here: 
  [DominiqueGarrett](https://github.com/DominiqueGarrett)  
  Dominique.garrett1212@yahoo.com
