# DUNKA DUNGEONS

# The purpose with this project

The purpose of my project is to have a hub outside of Discord for my World of Warcraft guild, to show potential new recruits what we're about, and where they can apply to join the guild. The site contains three pages with a home site, gallery and an application windoww. Application is done via a form.

The target audience are World of Warcraft players on Firemaw with an interest of joining our guild.

This website is the first of five projects that needs to be completed in order to receive a diploma in Software Development from The Code Institute.

Requirements for the project is that the website has to be static and responsive using HTML5 and CSS3.

A live version of the project can be found here - 

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
* Find information about the guild
* See when the next irl meetup is
* Be able to apply to the guild
* See the recruitment status

### Requirements
A responsive website that incorporates the languages I have learned so far, with a development process that needs to be well documented through a version controls system such as GitHub.

Required technologies: HTML, CSS


### Design
This is my first ever coding project, thus I've been quite inspired by the "Love Running" project I did earlier in the course. My design of the header and the footer have been inspired by that project. 

### Colour
The colour palette is created with regards to my hero image to get the colours unified. The hero image is the endpboss for the expansion we're currently playing so it fits well with the theme, as we are a raidingguild. I created it using [Adobe Color](https://color.adobe.com/sv/create/color-wheel)

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

   /picture of header

   #### Hero Header Section
   - It contains a hero image. I've based the entire colourscheme of this picture as the character in the image is very iconic for the expansion the guild is currently playing.

   /picture of hero section

   #### About us Section

   - This section is devided in two parts. About us, and recruitment status. The first part is some basic information about the guild, as how we formed, and how long it's been running.
   - The second section is about our recruitment status, and what we expect from our raiders.

   /pictures of both the sections

   #### Meetup

   - This section contains information about when the next meetup is, and where.
   - The purpose of this section is to advertise that we do meetups irl, and also for members to know when, where it is, and where they can sign up for it.

   #### Footer Section

   - The footer contains our social media links, which is a link to our Discord channel, and our Warcraft logs.
   - The purpose of this is so that people can easily join our discord for more information and to get in contact with us.

   /picture of footer

   #### Gallery

   - The galleries purpose it to share some pictures either from big moments in the game such as bosskills, but also pictures from IRL from our meetups, as we tend to meetup 2-3 times per year in different countries. I've used a flexbox for this part so it's easy to further add pictures.

   #### Application

   - This section is our application form, for if someone is interested in joining our guild. 


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
3. In the application and applied pages, the menu wouldn't stay at the top, and they would sort of get in the middle of the logo and menu on bigger screens.
- Solution: Added a few br and it got in the right position.
4. In my application form at one point I could select all three, dps tank and healer.
- Solution: I had the name different on all of them initially, but then I changed to the same thing and after that I can only select one.

   
   

