# *Note: the site is called BiaBook but the repository name is biablog* #

# BiaBook Testing Details #


[Main README.md file](https://github.com/AlexNexton/biablog/blob/master/README.md)

[View the live project here.](https://biablog.herokuapp.com/)

---

## Table of Contents ##

- [Automated Testing](#automated-testing)
  - [Validation Services](#validation-services)
- [Manual Testing](#manual-testing) 
  - [Testing undertaken on desktop](#testing-undertaken-on-desktop)
  - [Testing undertaken on tablet and phone devices](#testing-undertaken-on-tablet-and-phone-devices)
  - [User Stories Testing](#user-stories-testing)
- [Bugs discovered](#bugs)
  - [Resolved bugs](#resolved-bugs)
  - [Unsolved Bugs](#unsolved-bugs)


---
## Automated Testing ##
 
### Validation Services ###

The following **validation services** and **linter** were used to check the validity of the website code.

- [W3C Markup Validation](https://validator.w3.org/) was used to validate HTML.
- [W3C CSS validation](https://jigsaw.w3.org/css-validator/) was used to validate CSS.
- [JSHint](https://jshint.com/) was used to validate JavaScript.
- [Chrome DevTools Lighthouse](https://developers.google.com/web/tools/lighthouse) is an open-source, automated tool for improving the quality of web pages. You can run it against any web page, public or requiring authentication. It has audits for performance, accessibility, progressive web apps, SEO and more.

---
## Manual Testing ##
--- 
 
### Testing undertaken on desktop ###

- Hardware:
    - Macbook Pro Laptop
    -  HP laptop
    - Dell 5590 Laptop
- Tested Operating Systems:
    - Windows 10
    - OSX 10.11          
- Tested Browsers:
    - Windows 10:
        - Chrome
        - Firefox
        - Edge 
    - OSX 10.11
        - Chrome
        - Firefox
        - Safari  

### Testing undertaken on tablet and phone devices ###

- Hardware:
    - iPad Pro 12.9"
    - iPad Pro 10.5"
    - iPhone XS Max
    - samsung a50
- Tested Operating Systems:
    - iOS 13.5.1
    - iPadOS 13.5.1
    - Android 10 with One UI 2.0
- Tested Browsers:
    - iOS / iPadOS
        - Chrome
        - Firefox
        - Edge

---
## User Stories Testing ##
---

- As a user, I would like to be able to search for recipes.

    1. Go to the page called **Recipes**(this page is rendered first).
    2. Looking at the page, type the recipe you're looking for following the placeholder text's guidence, to find a recipe.
    3. If the recipe is in the database, it will appear in the options below the search bar after the **search** button is pushed.


- As a user, I would like to register in order to have my own account.
- As a user, I would like to create a profile and upload a picture.  

    1. Go to the Nav-bar, which is rendered on all pages.
    2. Looking at the Nav-bar, click the **'Register'** page.
    3. Enter a username and password - the yellow text below gives the user examples.
    4. Click 'Register' button to finish creating profile page.
    5. Once there the user can upload a picture of their choosing.

-  As a user, I would like to view what recipes other users have created..

    1. Go to the Recipes page (using the nav-bar).
    2. The Rescipes are visibile just below the search bar.
    3. The user clicks on the recipe they wish to view and the recipe will open.


-  As a registered user, I would like to add, edit or delete my own recipes.
    
    1. Once a memeber the **add recipe** page in the nav-bar will turn orange.
    2. The user Clicks here to render the page.
    3. Once rendered, the user fills out the form and submits their recipe.
    4. Their recipe will appear at the bottom of the **Recipes** page.


- As a **user**, I want to be able to **contact** the website.

     1. Go to the anypage.
     2. Scroll down to the very bottom
     3. There is a phone number and email address for users to get in touch.
     

- As a **user**, I want to be able to access the site's if any **Social Media** platforms.

    1. Go to any page.
    2. Scroll down to the very bottom.
    3. Click either Facebook or Instagram.
    4. Here (if the site were real) you can view all of the websites merchandise.



#### Bugs ####

### Resolved bugs ###

- The Recipes page would not render.
  - I had to remove and re-add the *recipe_name* page on [Mongo DB Atlas](https://www.mongodb.com/cloud/atlas), this fixed the issue.
- I had issues with the card panels for the login and register pages on mobile view.
  - I set up two media queries in the Style.css folder which solved the problem.
- The code supplied by Code Institue for the input validation when adding a recipe kept turning red even after a selection had been selected.
 - I removed the css red colour in the jquery script.js file so that the bar would only turn green. A category must still be selected in order to add a recipe so the validation works.

#### Unsolved Bugs ####

- When a user signs in and hits the back page they are brought back to the login page yet if they hit the forward key are still logged in.
- Alternatively, if a user signs out but hits the back button at times they still have access to their profile.


