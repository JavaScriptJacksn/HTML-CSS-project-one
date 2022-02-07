# The Art of War Gym
---
![Am I Responive Image](/assets/images/Responsive.jpg)

# User Experience
---
## User Stories
- First Time Visitor Goals:
    - As a First Time Visitor, I wish to be able to access and understand the information about the gym.
    - As a First Time Visitor, I want to be able to quickly understand how to navigate the site to the sections I need.
    - As a First Time Visitor, I want to easily be able to access the social media sites of the gym along with their contact email for any questions I may have.
    - As a First Time Visitor, I want to be able to see the names and specialties of the staff running the gym to see if they are indeed experienced and of value to the gym’s members.
- Returning Visitor Goals:
    - As a Returning Visitor, I want to easily view further information including contact information.
    - As a Returning Visitor, I want to be able to easily navigate to the sign up page and easily provide my details for membership application (As it is usually not the first time viewing that visitors choose to sign up).
- Frequent Visitor Goals:
    - As a frequent visitor, I want to be able to review the changes to the top Lifts table to see changes to scores.
    - As a Frequent visitor I want to see if there are any new featured lifts or lift spotlights.
---
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
## Features
- Responsivity for all devices
- Sign up form with validation
- HTML semantics
- Accessibility in the forms of alt tags for images and aria-labels for links
---
## Technologies Used
- Languages Used
    - HTML
    - CSS
- Frameworks, Libraries and Programs
    - Google fonts
        - An import link at the start of the style.css file imports the Archivo 900 weight font and the Standard weight Roboto font.
    - Font Awesome
        - Taking inspiration from the Code Institute Love Running project, I used the same font awesome icons for the social media links in the footer for asetheic purposes, as those were the best looking for my site. These were imported through the script tag in the html pages.
    - Git
        - Git was used for version control.
    - Github
        - GitHub is used as both a repository for the storage of the project, and also as a live website hosting service with GitHub pages.
---
## Testing
The W3C HTML and CSS validators were used to validate the code after each major change and completion of each page. All errors and warnings are resolved and the code passes validation
- Index.html validation [screenshot](/assets/images/Index-validation.jpg)
- lifts.html validation [screenshot](/assets/images/lifts-validation.jpg)
- sign-up.html validation [screenshot](/assets/images/sign-up-validation.jpg)