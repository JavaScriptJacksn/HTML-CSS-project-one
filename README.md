# The Art of War Gym
---
![Am I Responive Image](/assets/images/Responsive.jpg)

# User Experience
---
## User Stories
- First Time Visitor Goals:
    - As a First Time Visitor, I wish to be able to access and understand the information about the gym.
    - As a First Time Visitor, I want to be able to quickly understand how to navigate the site to the sections I need.
    - As a First Time Visitor, I want to easily be able to access the social media sites of the gym along with their contact email for any questions I may have, along with the gym location for in-person visits.
    - As a First Time Visitor, I want to be able to see the names and specialties of the staff running the gym to see if they are indeed experienced and of value to the gym’s members.
- Returning Visitor Goals:
    - As a Returning Visitor, I want to be able to easily navigate to the sign up page and easily provide my details for membership application (As it is usually not the first time viewing that visitors choose to sign up).
- Frequent Visitor Goals:
    - As a frequent Visitor, I want to be able to review the changes to the top Lifts table to see changes to scores.
    - As a Frequent Visitor, I want to see if there are any new featured lifts or lift spotlights.
## Design
- Colour Scheme
    - Red, Black and a minor text colour of white
    - These colours reflect the ethos of the gym, along with the brutality of the sports it practices with a dark black and shadowed background to divs, and a blood red for headings and bold text.
- Typography
    - Archivo is a sans-serif font used for the headings as it is blocky and strong whilst looking clean and professional. I imported the bolder 900 weight font to improve this. 
    - Roboto is used as the text font as it pairs cleanly and suitably with the heading font giving a nice contrast of bold headings to lighter body text along with their text colour.
- Imagery
    - The hero image is that of UK powerlifter Eddie Hall’s deadlift 500kg, the world record at the time in 2016. I used this image for two main reasons. Firstly, it sends an immediate thematic message to visitors of the gym’s ethos. The raw nature of the bleeding nose and dark background pairs great with the blood red and black colour scheme.
    - I also added an overlay to the hero image of a black colour with an opacity of 0.65 to decrease its focus and shift its colour palette lower to fit with the rest of the site.
    - The gym background image was chosen as it reflects what the interior of a gym like The Art of War would look like. It also brings a visually appealing contrast to the text and div backgrounds which are black with an alpha opacity of 0.8
- Videos
    - I used both embedded videos using the video tag and a youtube iframe.
    - The embedded videos were implemented to show a mixture of current world records and impressive lifts that are easy to change with one link in the html as they are beaten.
    - The iframe video is a documentary/news report on famous bodybuilder and powerlifter greg doucette which has its place as a special spotlight longer-form video.
    - I also used the iframe for the longer video as it streams an embedded youtube page through the iframe rather than loading a large video file from the server hosting servers which improves site loading time and reliability.
---
# Features
- Responsivity for all devices
- Sign up form with validation
- HTML semantics
- Accessibility in the forms of alt tags for images and aria-labels for links
---
# Technologies Used
## Languages Used
- HTML
- CSS
## Frameworks, Libraries and Programs
- Google fonts
    - An import link at the start of the style.css file imports the Archivo 900 weight font and the Standard weight Roboto font.
- Font Awesome
    - Taking inspiration from the Code Institute Love Running project, I used the same font awesome icons for the social media links in the footer for asetheic purposes, as those were the best looking for my site. These were imported through the script tag in the html pages.
- Git
    - Git was used for version control.
- Github
    - GitHub is used as both a repository for the storage of the project, and also as a live website hosting service with GitHub pages.
---
# Testing
The W3C HTML and CSS validators were used to validate the code after each major change and completion of each page. All errors and warnings are resolved and the code passes validation
- Index page validation [screenshot](/assets/images/Index-validation.jpg)
- Lifts page validation [screenshot](/assets/images/lifts-validation.jpg)
- Sign Up page validation [screenshot](/assets/images/sign-up-validation.jpg)
- Stylesheet validation [screenshot](/assets/images/style-css-validation.jpg)

## Testing User stories from User Experience
- First Time Visitor Goals:
    - As a First Time Visitor, I wish to be able to access and understand the information about the gym.
        - Users are given an immediate interactive call to action 'Ready for war' bringing user down to the main content of information.
        - Users get a clear and semantically layed-out main body content under three headings to easily access the information they need.
    - As a First Time Visitor, I want to be able to quickly understand how to navigate the site to the sections I need.
        - The site is designed in a clear and understandable way with user expectations being met from page to page.
        - The nav bar has a hover pseudo-class which, along with the page titles and layouts allows users to easily determine which site they are on and which one they have yet to visit.
    - As a First Time Visitor, I want to easily be able to access the social media sites of the gym along with their contact email for any questions I may have, along with the gym location for in-person visits.
        - The social media links are clearly layed out under the map in the footer on the homepage.
        - The links carry over to each site footer for access at any point in the user experience.
        - The email contact is found in bold at the center of the sign up form for ease of access.
        - Users are also prompted in the main content towards where to find the gym with the map on the home page.
    - As a First Time Visitor, I want to be able to see the names and specialties of the staff running the gym to see if they are indeed experienced and of value to the gym’s members.
        - The information is presented asetetically and easily both after a short scroll or clicking the main ready for war call to action.
- Returning Visitor Goals:
    - As a Returning Visitor, I want to be able to easily navigate to the sign up page and easily provide my details for membership application (As it is usually not the first time viewing that visitors choose to sign up).
        - The sign up page along with further contact information (email) is located on the sign up page and is easily located in the navigation bar.
        - On the sign up page the email is used to fill blank space between the two columns in the form area, which flows well within the page styling and is easily seen by returning visitors.
- Frequent Visitor Goals:
    - As a frequent Visitor, I want to be able to review the changes to the top Lifts table to see changes to scores.
        - The table of lifts is easily navigated to even from new users to the site, so is no worry for returning or frequent visitors.
        - The table of lifts is also mentioned and linked to in the main content on the home page, as well as the navigation bar.
    - As a Frequent Visitor, I want to see if there are any new featured lifts or lift spotlights.
        - The featured lifts are positioned on the same page as the lifts table, just above them in inline blocks with descriptions and video controls.
        - The videos flow well within the site and on smaller screen sizes still fit nicely into the viewport size allowing users on all devices to use them successfully and with ease.
        - The iframe lift spotlight works well as it allows users to easily find it, as expected elements show the user that the lifts page scrolls down, as to let them know there is more to be seen. The iframe also flows will within the page.
## Further Testing
- The website was tested with Mozilla Firefox and Google Chrome developer tools.
- Firefox was primarily use for box model and css styling testing, whereas Chrome was used mostly for testing for responsiveness. However both were used for each tast interchangeably at times.
- Flexbox proved a learning curve, however with the testing processes I used all issues were resolved and much was learnt.
- Friends and family members were asked to review the website on their different devices throughout and at the end of the deveopment process.
- Such devices include:
    - iphone 6
    - iphone XR
    - Macbook Air
    - 2560x1440p Desktop Monitor
    - Microsoft Surface Pro 4
## Known Bugs
- With the flexbox footer, on some smaller viewport devices the footer pushes the copyright text content to the right slightly.
---
# Deployment
The project was successfully deployed to GitHub pages under this [link](https://javascriptjacksn.github.io/HTML-CSS-project-one-Art-of-War-Gym/index.html)
A few issues regarding deployment became prevelant after some final testing:
- Gitub pages did not load images correctly, which was discovered to be an issue with my Firefox DarkReader extention, and not the code itself.
- After initial deployment, I found that the responisveness changed on the live site, which was simply a syntax error that seemed to work on gitpod live preview but not on the deployed site.
- However, these minor inconsistencies between my gitpod preview and the live site were solved quickly and effectively and the site now operates as expected.
---
# Credits
## Code
- The social media icons and script code for their linking came from [Font Awesome.](https://fontawesome.com/)
- Archivo and Roboto fonts and their css import link came from [Google Fonts.](https://fonts.google.com/)
## Content
- The hero image came from the thumbnail of this [YouTube video.](https://www.youtube.com/watch?v=oHnh3XRFyDE)

- The gym background image came from [Wallpaper Safari.](https://wallpapersafari.com/w/dOBCZa)

- The featured lift videos were all trimmed down in length, and all came from the [Lifting Vault YouTube Channel](https://www.youtube.com/c/LiftingVault)

- The lift spotlight embedded YouTube video came from [Greg Doucette's YouTube Channel](https://www.youtube.com/watch?v=vDv9kMqxCA8)
## Aknowledgements
- My mentor Gerry for his great help and feedback at each stage of the process.
- The Code Institue support network for their help.
- Luke at The Learning People for his constant check ups and support.