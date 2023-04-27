# DUNKA DUNGEONS

# The purpose with this project

The purpose of my project is to have a hub outside of Discord for my World of Warcraft guild, to show potential new recruits what we're about, and where they can apply to join the guild. The site contains three pages with a home site, gallery and an application window. Application is done via a form.

The target audience are World of Warcraft players on Firemaw with an interest of joining our guild.

This website is the first of five projects that needs to be completed in order to receive a diploma in Software Development from The Code Institute.

Requirements for the project is that the website has to be static and responsive using HTML5 and CSS3.

A live version of the project can be found here - https://jikazu.github.io/dunka-dungeons/

# Index

+ [UX](#ux "UX")
   + [Site Purpose](#site-purpose "Site Purpose")
   + [Site Goal](#site-goal "Site Goal")
   + [Audience](#audience "Audience")
   + [User Goals](#user-goals "User Goals")
   + [Requirements](#requirements "Requirements")
+ [Design](#design "Design")
   + [Colour](#colour "Colour")
   + [Typography](#typography "Typography")
   + [Images](#images "Images")
+ [Features](#features "Features")
   + [Existing Features](#existing-features "Existing Features")
   + [Header and Navigation](#header-and-navigation-section "Header and Navigation")
   + [Hero Header Section](#hero-header-section "Hero Header Section")
   + [About Us Section](#about-us-section "About Us Section")
   + [Meetup Section](#meetup-section "Meetup Section")
   + [Footer Section](#footer-section "Footer Section")
   + [Gallery](#gallery "Gallery")
   + [Application](#application "Application")
   + [Application Form Dump](#application-form-dump "Application Form Dump")
+ [Technologies Used](#technologies-used "Technologies used")
+ [Testing](#testing "Testing")
   + [Validator Testing](#validator-testing "Validator Testing")
   + [Unfixed bugs](#unfixed-bugs "Unfixed bugs")
+ [Development and Deployment](#development-and-deployment "Development and Deployment")
+ [Content](#content "Content")
+ [Media](#media "Media")
+ [Credits](#credits "Credits")
+ [Great Webpages](#great-webpages "Great webpages")



- - -

# UX

### Site Purpose:
* This site is meant for anyone that plays World of Warcraft on the Firemaw server that is interested in knowing more about our guild, or have interest in joining the guild.
* It can also be used by our current members to check our current recruitment status or when the next meetup is.
 
### Site Goal:
* Is to inform anyone interested in our guild, what we are about, what they can expect when joining our guild and what we're currently recruiting.

### Audience:
* Anyone currently playing on Firemaw looking for a guild, or anyone interested in transferring to our server and join our guild.

### User goals:
* Find information about the guild.
* See when the next irl meetup is.
* Be able to apply to the guild.
* See the recruitment status.

### Requirements
A responsive website that incorporates the languages I have learned so far, with a development process that needs to be well documented through a version controls system such as GitHub.

Required technologies: HTML, CSS


## Design
This is my first ever coding project, and I've been quite inspired by the "Love Running" project I did earlier in the course. My design of the header and the footer have been inspired by that project. 

### Colour
The colour palette is created with regards to my hero image to get the colours unified. The hero image is the endboss for the expansion we're currently playing so it fits well with the theme, as we are a raiding guild. I created it using [Adobe Color](https://color.adobe.com/sv/create/color-wheel)

![colourpalette](/assets/readme-images/color-palette.png)

### Typography

The google font [Cabin](https://fonts.google.com/specimen/Cabin?query=cabin) was used for this project with a fallback of Sans-Serif. I've used font weight 600.  

### Images

I've borrowed one picture from the World of Wacraft website of the Lich King that I'm using as a hero image. All the photos in the gallery are either screenshots taken by me, or pictures taken by various guildmembers from several of our in real life meetups.

## Features

The dunka dungeons website has three areas. Home, Gallery and Apply.

Home consists of:
* About us section
* Recruitment info
* Meetup info

The gallery contains:
* 9 different pictures that can be built upon

Apply consists of:
* A form to fill in an application to join the guild. 


### Existing features

#### Header and Navigation Section

   - The Header consists of a text based logo section that is aligned to the left, and a menu that is aligned to the right with it's children aligned to the left.

   ![header](/assets/readme-images/header.png)

   #### Hero Header Section
   - It contains a hero image. I've based the entire colourscheme of this picture as the character in the image is very iconic for the expansion the guild is currently playing.

   ![hero picture](/assets/readme-images/hero.png)

   #### About us Section

   - This section is devided in two parts. About us, and recruitment status. The first part is some basic information about the guild, as how we formed, and how long it's been running.
   - The second section is about our recruitment status, and what we expect from our raiders.

   #### Meetup Section

   - This section contains information about when the next meetup is, and where.
   - The purpose of this section is to advertise that we do meetups irl, and also for members to know when, where it is, and where they can sign up for it.

   ![indexpage](/assets/readme-images/about.png)

   #### Footer Section

   - The footer contains our social media links, which is a link to our Discord channel, and our Warcraft logs.
   - The purpose of this is so that people can easily join our discord for more information and to get in contact with us.

   ![footer](/assets/readme-images/footer.png)

   #### Gallery

   - The galleries purpose it to share some pictures either from big moments in the game such as bosskills, but also pictures from IRL from our meetups, as we tend to meetup 2-3 times per year in different countries. I've used a flexbox for this part so it's easy to further add pictures.

   ![gallery](/assets/readme-images/gallery.png)

   #### Application

   - This section is our application form, for if someone is interested in joining our guild. 

   ![applicationform](/assets/readme-images/form.png)

   #### Application Form Dump

   - This section is the landingpage when you've submitted an application.

   ![formdump](/assets/readme-images/formdump.png)


   ## Technologies used

   - [HTML](https://en.wikipedia.org/wiki/HTML)
   - [CSS](https://en.wikipedia.org/wiki/CSS)

   ## Testing

Test of functionality and appearance of the website has have been dealt with troughout the developemt process. 
Tests has been conducted with Google Chrome, Firefox and on different devices.

I've listed my main issues here:

1. The About us section and the recruitment section on the index page did not look good on smaller screens, with poor performance. 
- Solution: Put them in a flexbox instead of doing floats, and now the responsiveness and positioning looks much better along with a media query.
2. Footer was not staying in the bottom of the apply or gallery when viewing on smaller screens
- Solution: I put the form in a flexbox, and then it somehow stays in the bottom on smaller screens.
3. In the application and applied pages, the menu wouldn't stay at the top, and the form and text would sort of get in the middle of the logo and menu on bigger screens.
- Solution: Added a few br and it got in the right position.
4. In my application form at one point I could select all three, dps tank and healer.
- Solution: I had the name different on all of them initially, but then I changed to the same thing and after that I can only select one.

Other than the above, I had some spelling mistakes and open brackets etc, but that was remedied after using the validator as the errors showed up there.

### Validator Testing

-HTML
   - One error is returned when running it through the official [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjikazu.github.io%2Fdunka-dungeons%2F)


![W3C HTML Validator](/assets/readme-images/validator-html.png)

- CSS
- No errors were returned when running it through the official [Jigsaw Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjikazu.github.io%2Fdunka-dungeons%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

![Jigsaw Validator](/assets/readme-images/validator-css.png)

- Lighthouse testing

![Lighthouse testing score](/assets/readme-images/lighthouse.png)

   
### Unfixed Bugs

1. The footer of the index page only, when viewing it on smaller screens, get stuck in the middle of the page and doesn't stay in the very bottom.

All other known bugs are in the [Testing](#testing) section, with their solution. 

## Development and Deployment

The development environment used for this project was GitPod. To track the development stage and handle version control I've done regular commits and pushes sto GitHub. The GitPod environment was created by using a template provided by Code Institute. 

The live version of the project is deployed at GitHub pages.

The procedure for deployment followed the "Creating your site" steps provided in [GitHub Docs.](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

1. Log into GitHub.
2. Locate the GitHub Repository that shall be deployed live.
3. At the top of the repository, select Settings from the menu items.
4. Scroll down the Settings page to the ”GitHub Pages" section.
5. At the ”Source” section choose ”main” as Branch and root as folder and click ”Save”
6. The website will deploy and the pages refreshes to provide the live link to the project.

The live link can be found here: https://jikazu.github.io/dunka-dungeons/
   

## Content

- All content on this site has been produced by the author of this project. This is a real guild on the server of Firemaw which the author is a member of.
- The design of this project is inspired by the "Love running" project. Code has been borrowed from that project, such as the menu annd footer.
- The icons in the footer was taken from [Font Awesome](https://fontawesome.com/).

## Media

- The hero image is borrowed from [Blizzard Entertainment](https://wowclassic.blizzard.com/en-us/). I do not own the Copyright, and I'm using it for educational purposes.
- The pictures in the gallery are both screenshots from the game, and also pictures taken by various guildmembers from our irl meetups. I've gotten permission from them to use the pictures in my project. 

## Credits

Many thanks to:

Martina Terlevic
 - My mentor

 ### Great webpages

 Sites that I've used a lot during this project to look up various things are:

 https://www.w3schools.com/
 https://www.youtube.com
 https://flexboxfroggy.com/

 And all the previous lessons in HTML-Essentials, CSS-Essentials and the Walkthrough project ”Love Running”.

 Kind Regards,

 [Back to top](#dunka-dungeons)