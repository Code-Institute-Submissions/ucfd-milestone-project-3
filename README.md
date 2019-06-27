## User Centric Frontend Development Milestone Project

#### The Monkees Website

This website is created for a 60's pop band, with around 50 years experience of performing. They have released many albums and video clips and want to use their website to make all this materials available for their fans.
Also, they have started their presence on social media to keep their fans updated.

The main goals of this website:
- Keep the fans updated with the latest news of the band.
- Showcase the latest musics and videos.
- Make it possible to be contacted directly by fans and event planers.
- Links to their Facebook, Twitter and YouTube pages.

### Demo
A demo can be viewed on Github Pages [here](https://adelbakhshi.github.io/ucfd-milestone-project/).

### UX
The aim was to design a simple and easy to use website as their target audience covers a wide age range. The website is single page which could make navigating through website easier with just scrolling.

##### User Stories
1. As a visitor to the site, I want to easily go through the sections in the site, so that I can quickly find what I want.
2. As a visitor to the site, I want to see an eye-catching cover of the band so, that I know I am on the right website.
3. As a visitor to the site, I want to see the latest media (video and audio) of the band, so that I can find out about the latest released.
4. As a visitor to the site, I want to be able to read the latest news of the band, so that I can stay updated.
5. As a visitor to the site, I want to be able to communicate with the band, so I can show my support and interest to them.
6. As a visitor to the site, I want to find the social network pages of the band, so I can follow them.


##### Wireframe
To make the wireframe [Figma](http://figma.com) was used. However, during the process some changes have been done.<br/>The wireframe is a PDF file which can be seen [here](/wireframe/Monkees-wirefram.pdf) 

### Technologies Used
1. HTML
2. CSS
3. Bootstrap (4.3.1)
4. JQuery

### Features
This website is a single page website and contains five sections. Each section has a title on the top left side to make sure the user don't get lost.</br> The navigation is always on top of the screen so the user can jump to the required section at any time.

##### Home Section
This section is a full screen photo of band and their popular logo which will be shown in all the screen sizes. On small screens most of the background cover can not be viewed but the logo of the band on the bottom of the screen represent the identity of the website.

##### Media Section
In media section page is divided in two sections. the left side user can see the two latest videos of the band that can be watch in a modal window by clicking on watch button and on the right side the last three album that have been released.

##### News Section
In this section the three latest news of the band will be shown. A photo is included to news block which, will not be shown in the small size screens.

##### Band Section
This section contains an old photo of the band with a short biography of the band on the side.

##### Contact Section
In this section the contact form can be used to contact the band. All the fields are required to be filled and email format has to be correct otherwise the error message will appear.


### Testing
This site was tested on Chrome, Safari and different mobile devices. 

 1. Watch videos (media page):
    1. Went to the Media section
    2. clicked on watch buttons and modal window opened. Clicked play button and video plays.
    3. Tried to close the window by clicking on the screen (not on the video). The window disappeared but the sound was still playing.
    4. Stopped the video then closed the window and it worked as expected.  

 2. Contact Form
    1. Went to the contact section
    2. Tried to submit the empty form and the error message about the required fields appears.
    3. Submitted the form with an invalid email address and the relevant error message appears
    4. Submitted the form with valid inputs, there was no error.

 3. Small Screen (mobile)
    1. Open the Home section on mobile (iOS). The background image was zoomed-in.

 4. Small Screen - Navigation
    1. Clicked on navigation button
    2. The menu opened, after selection the menu stayed open
    3. Added JavaScript code and the menu closes ofter selection 


### Deployment
This site is hosted using Github Pages, uses the master branch. The deployed site will be updated automatically with new commit to the master branch.<br/>Demo can be viewed [here](https://adelbakhshi.github.io/ucfd-milestone-project/).



### Media

- The photo in the home section was taken from [inquisitr](https://www.inquisitr.com/2771903/the-monkees-celebrate-50-year-anniversary-with-new-album-tour)
- The photo in the band section was taken from [wikipedia](https://en.wikipedia.org/wiki/The_Monkees#/media/File:The_Monkees_1966.JPG)
- The Logo in the navigation was taken from [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Monkees-logo.png)

### Acknowledgements
To fix the issue with the collapsed navigation, my mentor Mr. Nishant Kumar helped me to add a JavaScript code.