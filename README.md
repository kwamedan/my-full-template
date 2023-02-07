/**`python3 -m http.server`/**
# Kwame Project Milestone - Online Gym Website
## UX
### Project Goals 

The primary goal of this website is to attract as well as retain clients to attend gyms. The target is to raise revenue for the gym and increase the popularity of the gym. Target group is any demographic age ranging 16 to 65. 
### Client Goals

* The target group is for individuals between 16 and 65 years old as children are too young to workout and older people may not have the capabilities to attend the gym or be a frequent customer throughout the gym. 
* I plan to make the webpage as visually pleasing as possible as there are many other competitors that I will have to try and beat to gain the support of a client. 
* I aim to make it an easy sign up for users to create a membership account so they do not spend too much navigating the website and lose concentration, delaying the time they take to sign up or stop them signing up in all.
* I plan to make the menu page the initial page the user sees where they can easily navigate to different sections of the website.It'll contain clear information on how to access the gym. I would like to display an account link where the user can:
⋅⋅⋅ access their account details
⋅⋅* a link to access a personal trainer
⋅⋅* a link to the 'bar and cafe'
⋅⋅* display opening/closing times and location
⋅⋅* contact information
⋅⋅* refer a friend reward
⋅⋅* social media links at the footer of the page  
⋅⋅* an 'About' page that will tell the user about our gym facilities, history and famous clients.

### Developer and Business Goals
I hope to make the design as attractive as possible so the user can have a positive 1st impression. I will also design and structure the website logically to keep the user on the webpage.
The website will have a set colour scheme that will flow throughout each webpage and this will satisfy each user and appear more attractive. 
I will include 3 different pages that the user can click which will open in a separate tab:
* The application to create an account which will be strucured as a form
* The application to get a personal trainer which will also be structured as a form
* The various social media links at the footer of each page
The use of separate tabs will make it simple for the user to fill out the form whilst still having the flexibility to navigate throughout the website if need be. 

I will make my program robust by having 'required' entry forms and create clear buttons with 'alt' messages so they can see exactly what will happen once they click the button. 

I will display positive images of people smiling and interacting throughout the website to give the idea that going to the gym is not only fun but also a sociable environment with many people who are willing to help. 

I will include a mini, interactive clip where the user can see the gym in video form and gain a better understanding of what it will entail. 

### User Stories

As an adult or young adult in the current day and age I want to:
* Easily see the location of the gym as well as opening/closing times
* Easily navigate and access a variety of features with buttons and links
* Have a menu page that I can easily navigate and understand
* Use buttons and links to get preview images, videos and reviews into what the gym looks like
* Read about reviews of the gym
* Have a link to access a personal trainer
* To understand and relate to icons  
* Fill out a sign-up form for an account/personal trainer
* Access social media links 
* See an interactive video of the gym that I can pause/play at anytime 
* Leave me with a positive experience 

### Design Choices
My aim is to make the website positive, efficient and easy to use so there is not much time wasted trying to navigate the website or by reading excess information. Following on from this, I desire to include this set of features:

#### Font
The primary font will be 'Open Sans' as it has been the most popular font used by the largest gyms across the UK, so it will create familiarity to ex gym users but also be simple to read for new users.

The secondary font will be 'sans-serif' as it compliments 'Open Sans' well whilst also being an easy read for any user.

#### Icons
All icons displayed will be relatable to its section of text/image and easily recognisable by all humans.

#### Colours
The primary colours display throughout the website will be green and white as it presents an optimistic feel but green will also give users a sense of nature which will help them feel relaxed and place them in a peaceful mood. White also contrasts well with green but not too much that it gives a negative connotation. 

* Any other colours used will be selected experimentally using 'rgba' to inclue opacity where needed

#### Backgrounds and Images
I will display different backgrounds for each page, relating the page which the user is on.

* The main menu page will have a 'gym' setting background which introduces the user
* The personal trainer page will have a 'personal trainer and client at the gym'
* The application page will have a positive background of someone smiling so they can picture themselves with that same emotion once they sign up.

#### Video file
This file will show the user a preview of the gym and features to enjoy once a member. It will also be interactive and allow the user to pause/play the video.

### Wireframes

After reviewing and completing the wireframes, it has given me a better understanding of how my website would appear and appeal to the user. For this reason, I've decided to change sections and parts of the layout within my webstie:
* Firstly, I have decided to use a fixed header and footer throughout each page so there is a consistent flow throughout the website
* I have also decided to not include the 'personal assistant' section as a separate page as there isn't enough detail or relevance of this to give it its own page
* I have decided to not include a video clip or a 'refer a friend' section as it gives the user too much information to deal with and this can be included later on in another cycle once the user has signed up. 

## Features
* 
* 
* 

## Technologies Used
Bootstrap CDN to format my website:
[Bootstrap CDN](https://getbootstrap.com/)

Fontawesome icon used for placing icons into my website: 
[Fontawesome Icons](https://fontawesome.com/v5/search?o=r&m=free)

## Testing
### Bugs

* Content has been pushed to the left-side of the page so certain characters are missing on the page:

To solve this, I have decided to use the class: 'container-fluid' from bootstrap to push all content into the main frame:

* The contact number has been displayed below the navbar and to the left of the page:

I have included some CSS styling to solve this. First I created a class for the 'span' and within style.css I floated the content to the right and created the code for it before the 'h1' header so it appeared right at the top:

* The reviews has been displayed below the main content and to the left of the page:

Similar to the contact number, I have set the float to right and created a class for the review section to float all its content:

* The icons have been displayed too close to their parent text:

I have since decided to add padding to the relevant side required of each icon to give it more breathing space:

* When creating a fixed header, the content from below the header interferes with it:
I have decided to create a grid
To combat this, I have decided to add padding to each icon relative to its position and set the z-index of the header to a lower value than the content below it. I also received additional suppor to solve this from [Help](https://stackoverflow.com/questions/46555609/displaying-content-below-a-fixed-header):

* When inputting the image for the account page, it was difficult to center it between both forms:

To solve this, I decided to give the image its own ID as well as size and position:



## Deployment

## Credits
### Content
### Media
Hero Image used in the accounts page: [Account Image](https://www.pexels.com/photo/various-fitness-machines-in-modern-spacious-gym-7031706/)

Hero Image used in the cafe page: [Cafe Image](https://www.pexels.com/photo/black-and-white-ceramic-mug-1813466/)

### Code
Template code for the fixed navbar at the top of each homepage was provided by: [Navbar](https://getbootstrap.com/docs/4.1/components/navbar/)

Code used to help g


Google support to help insert the map into the footer of the page:
[Google Help](https://support.google.com/maps/answer/144361?hl=en-GB&co=GENIE.Platform%3DDesktop#:~:text=Embed%20a%20map%20or%20directions&text=Click%20Share%20or%20embed%20map,Click%20Embed%20map.&text=Copy%20the%20text%20in%20the,of%20your%20website%20or%20blog.)
### Acknowledgements
