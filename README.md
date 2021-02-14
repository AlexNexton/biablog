# BiaBook

### [BiaBook Live Site](https://biablog.herokuapp.com//)

### [GitHub Repository](https://github.com/AlexNexton/biablog)

![Responsive]()

BiaBook (where 'bia' is the Irish word for food) is my Milestone 3 project.
It is part of the Fullstack Software Development Course of [Code Institute](https://codeinstitute.net/).

# Table of Contents

**<details><summary>Project overview</summary>**
* [**_Project overview_**](#project-overview)
* [**_User Stories_**](#user-stories)
* [**_Admin Stories_**](#admin-stories)
</details>

**<details><summary>UX</summary>**
* [**_Strategy Plane_**](#strategy-plane)
* [**_Scope Plane_**](#scope-plane)
* [**_Structure Plane_**](#structure-plane)
* [**_Skeleton Plane_**](#skeleton-plane)
* [**_Surface Plane_**](#surface-plane)
    * [_Color Scheme_](#color-scheme)
    * [_Typography_](#typography)
    * [_Media_](#Media)
    * [_Wireframes_](#wireframes)
</details>

**<details><summary>Features</summary>**
* [**_Existing Features_**](#existing-features)
* [**_Features Left to Implement_**](#features-left-to-implement)
</details>

**<details><summary>Technologies Used</summary>**
* [**_Libraries_**](#libraries)
* [**_Version Control_**](#version-control)
</details>

**<details><summary>Accessibility</summary>**
* [**_Semantics_**](#semantics)
</details>

**<details><summary>Testing</summary>**
* [**_Testing_**](#testing)
</details>

**<details><summary>Deployment</summary>**
* [**Deployment**](#deployment)
</details>

**<details><summary>Credits</summary>**
* [**_Content_**](#content)
* [**_Acknowledgements_**](#acknowledgements)
</details>

---

# Project Overview

BiaBook is a simple recipe website where users can share their recipes and view other's.
---

### User Stories

-  As a user, I would like to be able to search for recipes.
-  As a user, I would like to create a profile and upload a picture.  
-  As a user, I would like to view what recipes other users have created.
-  As a user, I would like to register in order to have my own account.
-  As a registered user, I would like to add, edit or delete my own recipes.


### Admin Stories

- As a site owner, I want to create a site that is mobile ready.
- As a site owner, I want to be able to add or remove categories.
- As a site owner, I want my users to be able to sign up to the website.
- As a site owner, I want my users to be able to connect with the owner/team via social media channels.
- Testing information for User Stories can be found in a separate testing.md file.
---

---

## UX Planes

### Strategy Plane

- Project Goals: The goal of this project was to create a simple website where users could share and view other recipes. They could create their very own account and learn new cuisines from other users.

- Content: The content is determined by the users and presented in a uniform and clear manner.

#### Personal Goals

- To learn and practice frontend and backend programming together for the first time. To combine the use of HTML, CSS, Materialize and JavaScript with Python, MongoDB, Flask and Jinja.

### Scope Plane

- A website where users can showcase their recipe with simplicity.
- A website with minimal but yet subtle interaction amongst the users.
- Future Technologies would be a fully interactive profile page for each user.


### Structure Plane
- Nav bar on each page with *Recipes*, *Login* and *Register* - *add recipe* is available once a member.
- Recipes: A showcase of user recipes with a search bar to aid users in finding a particular recipe.
- Login: Where the user can access their profile by supplying their username and password.
- Register: Where a user can sign up and begin sharing recipes.
- Footer: to the social media sites.

### Skeleton Plane
#### Wireframes

-  designed the site mock-ups using balsamiq wireframes. Each image/pdf shows a page and how the displays would change on different screen sizes such as mobile, tablet and desktop.

### Surface Plane

- limited fonts and colour scheme

#### Design

A standard layout is fully responsive on mobile devices and larger screens.

#### Color Scheme

Colors are kept to a minimum in order to keep focus on the imagery of the recipes, chosen colousr are various shades of grey. Color scheme can be found on my Coolors profile: [Coolors]()

![Color Palette]()

#### Typography

 [Google Fonts](https://fonts.google.com/) were used across the site:

- [Vollkorn SC](https://fonts.google.com/specimen/Vollkorn+SC?selection.family=Reggae+One|Vollkorn+SC&sidebar.open=true&preview.text_type=custom) : Used throughout the entire site.

All images, and recipes are the authors own unless provided by other users. Logos are also produced by the author using Affinity Design.

- [Balsamiq Wireframe]()
 
##### back to [top](#table-of-contents)

---

# Features

## Existing Features

### Elements on every page
#### Navbar
- The navigation Bar.

- For visitors to the site who are not logged in, list items links are available for them to use.
    1. Recipes
    2. Register
    3. Login

- For users who are logged in, the list items are as follows: 
    1. Logout
    2. Add Recipes
    3. Profile
    4. Users

- Python determines if the user is logged in or not by checking `if 'user' in session` and passes this data to Jinja to display the correct navbar for the user.

- Using [Materializecss](https://materializecss.com/), on the smaller resolutions (tablet, mobile) the navbar collapses into a burger icon and opens from the side.

#### Footer

The Footer features:
- Contact section
- Copyright Information
- Links to social media platforms.
 
### Individual Pages


### Recipes

- This page contains:
    - a view of recipes from all the users.
    - If signed in, you can edit or delete your recipe.
    - You can open each collapsible to view the recipe contents and it's image.

### Register

- This page contains a form where users may register and be redirected to their profile. Below the form is a link to login.

### Login

- This page contains a form where users may login and be redirected to their profile. Below the form is a link to register.

### Logout

- Clicking 'Logout' ends a user session and redirects them to the 'Login' page.



# Future Features to Implement

- **Image Hosting** 

    Each image added to the recipes comes from a http: link, in the future I would love to make it so the user would be able to upload an image to the database.

-   **Profile Page**

    - The Profile page currently allows users to upload an image but they are unable to save it. I would like to add this feature later.
    - Also, I would like to make a profile page similar to one you might find on [facebook](www.facebook.com) where user could design it to their tast and like and/ favourite other user's recipes.
    - I would like to add a video platform where users could vlog their recipes and have others follow their content.

    

##### back to [top](#table-of-contents)

# Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) - Used throughout the site.
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html) - Used throughout the site.
- [JavaScript](https://www.javascript.com/) - Used to help features in [Materialize](https://materializecss.com/).
- [Materialize](https://materializecss.com/) - Used to aid responsive design and for componants such as modals.
- [Gitpod](https://code.visualstudio.com/) - Code Editor used to create the site.
- [GitHub](https://github.com/) - Used to host repos for the site.
- [Imgur](https://imgur.com/) - Used to host images for the site.

- [Chrome](https://developers.google.com/web/tools/chrome-devtools) - Used to test/ find a solution to a problem.
- [W3C Markup Validation Service](https://validator.w3.org/https://jigsaw.w3.org/) - Used to test code for errors.
- [Affinity Designer](https://affinity.serif.com/en-gb/) - Illustration software used to create logos and icons.

- [Balsamiq](https://balsamiq.com/?) - Used to create wireframes.
- [Tinypng](https://tinypng.com/) - Used to compress images.

- [Randomkeygen](https://randomkeygen.com/) - Used to generate random keys.
- [Kaffeine](https://kaffeine.herokuapp.com/) - Used to keep Heroku app from falling asleep.
- [Uptime Robot](https://uptimerobot.com/) - Used to keep Heroku app from falling.

###  Back-end 

- [Python](https://www.python.org/) - backend programming Language.
- [Flask](https://flask.palletsprojects.com/en/1.1.x/) - Python framework For pagination, etc.
- [Dnspython](https://www.dnspython.org/)-  DNS toolkit for Python.
- [Heroku](https://www.heroku.com) - Cloud application platform. 
- [Mongo DB Atlas](https://www.mongodb.com/cloud/atlas) - non relational, NO-SQL Database - Cloud based MongoDB server.
 
###  Front-end 

- [Javascript](https://www.javascript.com/) - For auto-complete, navbar, etc.
- [Jquery](https://jquery.com/) - For auto-complete, navbar, etc.
- [Materialize](https://materializecss.com/)- for clean front-end design >
 
### Version Control

- [Git](https://git-scm.com/) - used for version control
 
---

# Accessibility

### Semantics

- HTML5 Semantics used throughout (header, nav, main etc...)
- Language is set to english (`<html lang="en">`)

---

- Aria labels used throughout eg `<button id="submit" aria-label="submit" type="submit">`
- Alt Text: Alt text dynamically applied to images eg `alt="{{recipe.recipe_name}} image"`

# Testing

 - All testing and validation is contained within a separate .md file. <br> [View TESTING.md](TESTING.md)

# Deployment

### To Create a Clone of the BiaBook Repository and Run Locally
Cloning the repository makes a copy of the of the repository which you download and store on your machine locally.

To make a clone of BiaBook, follow the following steps:
1. Visit the main repository of by clicking here --> [biabook](https://github.com/AlexNexton/biablog)
1. Above all the repository files and folders, you will find two Green buttons. Click on the one displaying ‘Clone’ with a downward arrow and a download icon.
1. With the ‘HTTPS’ method selected, click the ‘copy’ button next to the URL. Here you will find the link you will need to copy. The link to copy BiaBook is: https://github.com/AlexNexton/biablog
1. Open the working directory where you want the repository to be cloned to, and in the terminal use the command and hit enter: 
        git clone https://github.com/AlexNexton/biablog.git
1. All the files will now be cloned into your chosen workspace.
1. Add/create a env.py file with the following details:
	    Import os
	    os.environ.setdefault("IP", "To be added by user")
        os.environ.setdefault("PORT", "To be added by user")
        os.environ.setdefault("SECRET_KEY", "To be added by user")
        os.environ.setdefault("MONGO_URI", "To be added by user")
        os.environ.setdefault("MONGO_DBNAME", "To be added by user")

Do not commit this page.

1. Create a file named  .gitignore  with the contents simply .env.py

1. To install the modules required on the requirements.txt file, run the command:
	pip3 install -r requirements.txt

1. You can run the code using the command:
	python3 app.py in the terminal.



## Secret Key & Key Variables
Secret keys should not be pushed to GitHub, or shared with anyone. To avoid this happening, I included my Secret Key and key variables in a file which is stored locally.

The file env.py includes these key variables and secret key. 

To stop this file being pushed to GitHub when commits are made and pushed, I created a .gitignore file which included the file name within it. Every time commits are made and pushed, the env.py file is ignored.

## MongoDB database Elements Used

###### categories
```
_id: <ObjectId>
category_name: <String>
```

###### Recipes
```
_id: <ObjectId>
category_name: <String>
recipe_name: <String>
recipe_ingredients: <String>
recipe_method: <String>
recipe_image: <String>
created_by: <String>

```

###### users
```
_id: <ObjectId>
username: <String>
password: <String>
``` 

### Deploying Website To Heroku 

 

By deploying BiaBook to [Heroku](https://heroku.com/), I was able to run my Python app and view a live version of the website which updated with each push I made. This link is also shareable to other users to be able to test the site.

1. In the terminal, I created a requirements.txt and Procfile using the following commands:
    1. pip3 freeze –local > requirements.txt
    1. echo web: python app.py > Procfile (be sure to create this file with a capital P)
1. Commit the new files to GitHub
1. Within my [Heroku](https://heroku.com/) account I created a new App called *'biablog'* and chose the region closes to me, Europe.
1. Within the deploy sections which opened automatically after creating the app, I selected the Deployment Method of Connecting to GitHub via the logo. 
1. Beneath this, I typed the GitHub repository name *'biablog'* and hit search. When the correct repository was found I clicked the ‘connect’ button.
1. Next, I clicked on ‘Settings’, then in Config Vars, I clicked ‘Reveal config Vars’. I filled out the Config Vars with the following information:

Config Vars | Config Vars
------------ | -------------
IP | 0.0.0.0
PORT | 5000
SECRET_KEY | To be added by user
MONGO_URI | `<link to your MongoDB database>`
MONGO_DBNAME | To be added by user

*Note: your MONGO_URI and SECRET_KEY must match the ones you entered in 'env.py' file*

7. In Deploy, I clicked ‘Enable Automatic Deploys’ and deployed from the Master branch.
8.	Follow this I then clicked ‘Deploy Branch’ and the app was deployed successfully at the URL [BiaFood](https://biablog.herokuapp.com/) which is *https://biablog.herokuapp.com/*
 
---

# Credits

## Content
### References:

- Firstly, The [Code Institute](https://codeinstitute.net/) Backend Mini project. A huge thank you!!

-  Github, Format of README modified from [Sean-Mc-Mahon](https://github.com/Sean-Mc-Mahon/McTasticRecipes) and [Michelle Clement](https://github.com/michellelclement/meatblog).

- [Stack overflow](https://stackoverflow.com/) for helping me fix parts of my code.

-  Google Fonts for font styles; https://fonts.google.com/

-  Button icons sourced from [Fontawesome](https://fontawesome.com/)

 

### Acknowledgements

 - Firstly, I would like to thank my friend John for believing I could get this project completed as it has personally been a difficult couple of months. 
 - Secondly, My Mother Caroline, for ringing me and helping me get my feet back on  the ground - Thanks Mom.
 - And finally, My friend Nessa, who is always there when I need her and who always pushes me to deliver my best - Thank you.
---

This project is for educational use only

##### back to [top](#table-of-contents)
