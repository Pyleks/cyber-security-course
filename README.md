# Offensive Cyber Security Course

Milestone Project 1 - User-Centric Frontend Development - Code Institute.


This is a Cyber security course website, exposing the visitors to a total of 8 tools and 8 techniques
to get them interested, but not intimidated or overwhelmed.

## UX
The website is designed to give the user access to relevant information on a single scrolling page,
as well guide them through the steps of cyber security to give them a stronger image of what the course
have to offer.

The visitors are provided multiple ways of contacting the company from physical address to phone and email.
as well the opportunity to sign up for a weekly newsletter in case they are not ready to make the final step
of signing up.
I allow the user to sign up at the top as well the bottom of the page.

Through the page I also included a video showcasing what type of opportunities are available within cyber security
space.

Strong colors have been choosen to clearly separate the topics as they scroll through the website
as well limiting the word count to keep the topic relevant and interesting.


## Technologies

1. HTML
1. CSS
1. Bootstrap
1. FontAwesome
1. jQuery
1. PopperJS

## Demo
The website can be viewed here: https://pyleks.github.io/cyber-security-course/

## Wireframe tool
For all wireframe work I have used
[Balsamiq](https://balsamiq.com)

## Features
The website uses Bootstrap Javascript and Modal for registration and pop-up messages, to
confirm for the client that they have registered.

## Planned features
Planning on adding a test hacking section to the website, where people can try themself at hacking a login field
to see if they enjoy the hacking process, before landing on a registration page, this will require
some light Javascript.

## Features not added
The input fields will work regardless if there is information or not.
This is due to "required" has not been added on the input forms due to not finding out how to do it
before modal get initiated.

## User Stories
> A company have just received a quote on having the network scanned, but want to see if it can be done in-house.

> A cyber security enthusiast want to up-skill his/her knowledge.

> A manager is looking for a cyber security course with good overview to bring to the meeting to convince the rest
that this is something to invest in.

> A company just experienced to be hacked and realized they need to up-skill their employees now.

> A network professional want to contact the company directly before making a decision.

## Testing
### Responsive Design
The website have been tested on all popular browsers to confirm all information is displayed
correct on (Chrome, Firefox, Edge).

**The following features have been tested.**

1. Navbar buttons on full screen and on mobile device sizes.
1. All buttons on the page brings up modal window as designed.
1. There is no required class implemented on the modal forms, so they work regardless of the information.
1. Footer icons link correctly and safely.
1. Fixed all bugs through W3 Validator for index.html and style.css.
1. 320 x 568 iPhone 5/SE has issues with hero text and button.


**Confirmed it is working with all popular device sizes below.**


1. 360 x 640 Galaxy S5
1. 375 x 667 iPhone 6/7/8
1. 375 x 812 iPhone X
1. 411 x 731 Pixel 2
1. 411 x 823 Pixel 2 XL
1. 414 x 736 iPhone 6/7/8 Plus
1. 768 x 1024 iPad
1. 1024 x 1366 iPad Pro


### Responsive scaling issues with headline
While the design works correct on all sizes mentioned above, except the Hero headline text, it breaks when scaling manually
between sizes, using responsive mode in developer tools, but works on the set sizes.
Ended up removing all media queries and about 700 lines of code, replaced with bootstrap to make it more
intuitive, however the nature of the hero text require replacement, and that caused major problems.


## Deployment
This website is live from GitHub, deployed directly from master branch, the website is updated automatically
when committing to the master branch. To deploy the website correctly on GitHub, the landing page
must be named `index.html`

To run this locally, you can clone this repository by pasting `git clone
https://github.com/pyleks/cyber-security-course.git` into your terminal.
To remove connection to this GitHub repository, just type `git remote rm origin` in your terminal

## Credits
### Content
All content is written by me, however some have been influenced and credited below.

### Hero Photo
Licence for this Photo have been purchased by me from
[Shutterstock](https://www.shutterstock.com/image-vector/cyber-security-concept-lock-symbol-lines-744399862)
And modified heavily using tools provided from the Shutterstock website, making the background completely black with a shining yellow lock.


### Logos
#### Bash (Bourne-Again Shell)
Bash logo have been downloaded from
[Bash Logo Media Assets](https://bashlogo.com/)


#### Python
Python logo have been downloaded from
[Python Logo](https://www.python.org/community/logos/)


#### Metasploit
Metasploit logo have been downloaded from
[pngkey](https://www.pngkey.com/detail/u2e6w7u2q8r5t4y3_this-metasploit-logo/)
Free transparent picture from pngkey with set resolution on 460x400.</p>

### Design Credits and Inspiration
* The tick underline on several words was inspired from Bootstrap own websites
[Bootstrap Focus.](https://themes.getbootstrap.com/product/focus/)

* Footer, was inspired from another Bootstrap websites
[Bootstrap CreateX.](https://themes.getbootstrap.com/product/createx-multipurpose-template-ui-kit/)

* Idea of using video was suggested by Mentor (Aaron Sinnott) but not the choice of video.
* Redesign of registration and adding a contact me form also suggested by Mentor (Aaron Sinnott).
* Adding each section to navbar also suggested by Mentor (Aaron Sinnott).