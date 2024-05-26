# Ride Guide: Walt Disney World

Ride Guide: Walt Disney World is a website that allows users to look for information for specific rides across all four Walt Disney World theme parks. The rides are seperated into two sections "Thrill Seekers" and "Family Fun", along side a competition page for users to enter. View the live site [here](https://mcamish29.github.io/ride-guide-wdw/index.html)

![responsive-screenshot](docs/readme-images/responsive-image.jpg)

## Features

### Site Wide
* Navigation Menu
    * Contains links to Home, Thrill Seekers, Family Fun and Competition pages and will be responsive on all devices
        *Responsive view on mobiles features a bar icon and drop down function for the users
    * The navigation bar will allow users to easily navigate between these pages within the site on any device

![nav-bar](docs/readme-images/nav-bar.jpg)
* Footer
    * The footer will contain links to social media websites that will open in new tabs. All icons are accesible to the visually impaired who may be using a screen reader, this is done by the use of aria labels.    

![footer](docs/readme-images/footer.jpg)
* Favicon
    * An on theme favicon will appear across all pages to allow the user to easily identify the page tabs

![favicon](docs/readme-images/favicon.jpg)

* 404 Page
    * A 404 error page has been created if a user goes to a broken link.
    * The users have the ability to navigate back to the home page via link found on the 404 error page, without using browsers back button

![404](docs/readme-images/404-error-page.jpg)

### Landing Page 
* Landing page hero image
    * The hero image will display Cinderlla Castle
    * There is a cover text in place to advise the user what the webpage is about

![landing-page-hero-image](docs/readme-images/index-hero-image.jpg)
* Body of landing page
    * Two paragraphs will feature on the landing page to advise users about Walt Disney World and how the rides have been split into groups
    * An additional link to the competition page can be found to assist users to enter
    * Three images will also be on the page showcasing rides found at Walt Disney World.
        * The images are accesible for visually impaired users who may be using a screen reader, this is done by the use of aria labels
    * All sections are responsive and will display on any device

![body-of-landing-page](docs/readme-images/index-body.jpg)

### Thrill Seekers Page
* Thrill seekers hero image
    * The hero image will display a thrill ride found in Walt Disney World
    * There is a cover text in place to advise the user of the current page they are on

![thrill-seekers-hero-image](docs/readme-images/thrill-seekers-hero-image.jpg)
* Body of thrill seekers page
    * A paragraph will feature on the thrill seekers page advising users of the thrill rides.
    * A table will contain the information of all rides advising users of ride name, minimum height requirement, location in the park and type of ride
        * Each table has a heading to advise the users of what park the rides are in
    * All sections are responsive and will display on any device

![thrill-seekers-body](docs/readme-images/thrill-seekers-body.jpg)

### Family Fun Page
* Family Fun hero image
    * The hero image will display a family ride found in Walt Disney World
    * There is a cover text in place to advise the user of the current page they are on

![family-fun-hero-image](docs/readme-images/family-fun-hero-image.jpg)
* Body of family fun page
    * A paragraph will feature on the family fun page advising users of the family rides.
    * A table will contain the information of all rides advising users of ride name, minimum height requirement, location in the park and type of ride
        * Each table has a heading to advise the users of what park the rides are in
    * All sections are responsive and will display on any device    
 
![family-fun-hero-image](docs/readme-images/family-fun-body.jpg)

### Competition Page
* Competition hero image
    * The hero image will display a selection of Disny ballons
    * There is a cover text in place to advie the user of the current page they are on

![family-fun-hero-image](docs/readme-images/competition-hero-image.jpg)
* Body of the competition page
    * A sentence will feature on the page to prompt the user to enter the form
    * A form is in place to allow the user to enter their information
        * First Name (required, type=text)
        * Last Name (required, type=text)
        * Email (required, type=email)
        * Paragraph question with radio buttons (type="radio" name="visit-time")
        * Paragraph question with text entry box (type="text")
        * Paragraph question with radio buttons (type="radio" name="visit-park")
    * On successful completion and submission of the survery form, the user will be navigsted to a thank-you.html displaying successful message    
   
![family-fun-hero-image](docs/readme-images/competition-body.jpg)

 ### Thank You  Page
 * Body of thank you page
    * The user will be greeted with a thank you heading, image and link back to home page

![family-fun-hero-image](docs/readme-images/thank-you-body.jpg)

### Existing Features

* Responsive design
* Survery form and thank you page
* Tables outlining ride information
* Additional link to competition page on index.html

### Features left to imlpement

* Survey form to be updated to post method for succesful competition results

* Video media of rides from YouTube

* Tables to be interactive to allow filtering and search capabilities

## Technologies
* HTML
    * HTML was used as the main language to develope the structure of the website
* CSS
    * An external file was used for the syling of the website
* Visual Studio Code
    * The development of the website was done using Visul Studio Code IDE
* GitHub
    * Source code is hosted on GitHub and deployed using Git Pages
* Git/ GitHub Desktop
    * Used to commint and pushcode during development
* Font Awesome
    * https://fontawesome.com/ was used to obtain icons for social media links and dropdown nav bar
* Tinyjpg
    * https://tinyjpg.com/ was used to reduce image sizes across website
* Flaticon.com
    * https://www.flaticon.com/ was used to obtain favicon
*  Convertio.co
    * https://convertio.co/ was used to convert jpg & png images into webp
* Pexels
    * https://www.pexels.com/ was used to obtain free stock images used across website 

## Testing

### Responsiveness

All of the web pages were tested to show responsiveness from 280px upwards.

**Steps taken to test responsivess:**

1. Open browser
2. Navigate to [Ride Guide: Walt Disney World](https://mcamish29.github.io/ride-guide-wdw/index.html)
3. Open developer tools by right clicking and selecting inspect
4. At the top of the page reduce dimensions to 280px x 858px 
5. click and drage the responsive window to maximum width

**Expected:** 

Fully responsive website across all pages with no images or content being stretched or warped
No horizontal scroll present
Elements no overlapping creating a bad user experience

**Actual**

The beahaviour of the website was as expected with the exception of content overlapping on Thrill Seekers and Family Funy pages creating a horizontal scroll bar 

### Devices

The website was also tested on below devices to ensure no responsive issues

- Samsung Galaxy s22 Ultra
- Apple iPad prod

### Accessibility

[Wave Accessibility](https://wave.webaim.org/) was used during development and final stages of testing to check for any accessibility issues.

Issue: Contrast errors we found on Thrill Seekers, Family Fun and Competition page due to font color

Fix: Font color adjusted to matching theming of page



