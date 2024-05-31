# Yogaworld Website 
Yogaworld is a fictional Yoga Studio that provides Yoga classes for the people of Jump Village Barnsley. Their motto is to exercise and empower through keeping the body supple. The site's target audience is everyone who wants to join a yoga class, people looking to try new things and those who want to promote better health through exercise. The website is a great place to find information on the studio and book a session 

<img src="documentation/mockup1-600.png" width="600"></p>

## Table of Contents: 
* [User Experience](#user-experience-and-interface(UX/UI))
* [Design](#design )
* [Wireframe](#wireFrame)
* [Features](#features)
* [Testing](#testing)
* [Deployment](#deployment)
* [Credits](#credits)

* ## User Experience and Interface(UX/UI) 
#### First Time Visitor Goals  
+ As a first time visitor to the site, I want to be able to easily recognise what the business is about and who it is for.
+ The first time I use the site, I would like to be able to find it easy to navigate through the site to find more content using familiar web assets such as link placements and icons.
+ I would like to be able to see a menu of classes being offered to see if they appeal to me and if they suit my ability level in yoga.  
+ I would like to see where the studio is situated and get directions.

+ #### Returning Visitor Goals  
+ As a returning visitor, I would like to check for any new classes offered.
+ I would like to be able to check if new classes have been added.
+ I want to be able to find the best way to contact the business for questions that i have.
+ I would like to contact the business to leave some positive feedback.  
****
## Design  
### Colour Scheme
+ I chose to use a light pink and green and brown for the yoga studios colour scheme. I feel this will give it an earthy healthy vibe
+ According to my research these colors are often used on yoga websites
+ I wanted to use the color green to promote a healthy feel to the site
### Typography
+ I used Arial and Merriweather as the main fonts.
+ ## WireFrame
I used the Balsamic website to create the wireframe for the yogaworld website. Having decided on the Strategy, Scope and Structure planes, I set about planning its Skeleton and what would become my vision of the Surface Plane.
* Home Page WireFrame (Windows)
<p align="center">
<img src="documentation/balsamiq-home-page.png" width="200"></p>

* Menu Page WireFrame (IPhone)
<p align="center">
<img src="documentation/balsamiq-menu-page.png" width="200"></p>

* Contact Page WireFrame (IPad)
<p align="center">
<img src="documentation/balsamiq-contact-page.png" width="200"></p>

## Features
#### Navigation
The page's navigation Bar is situated at the top of the screen.  It is the same on all pages. It appears on all pages, so the user has no need to use the back button.
  * The Links are situated on the top right of the page and will navigate the user to the Home Page, the Classes Page and the Contact Page.
    * The active page link has lightgreen background colour for user clarity as to what page they are on at the moment.
  * The Yogaworld name logo is situated on the top left of the page and is also a link back to the top of the Home Page if clicked.

  * #### Landing Page
<img src="documentation/landing-page-600.png" width="600"></p>

The Home/Landing page is an easy on the eye web page. 
  * About Us Section
    * The About us Section gives a brief description of the business, some of the classes that are available.
  Below that are some extra bullet points to note, in the form of images, to reduce reading time thus giving the user a more positive experience of learning about the business.
  * Ashtanga Classes
  * Pregnant Yoga Classes
  * Postnatal Yoga Classes
  * Information Section
    * The information section outlines the studio's opening hours and a Google Map for directions to the shop.
  * Footer Section
    * The Footer, identical on each page, shares links to the Yoga studio's social media sites for added engagement. When clicked, the links will open in a new tab to allow easy user navigation.  It also contains the site's copyright icon.
   
    * #### Classes Page
<img src="documentation/classes-page-600.png" width="600"></p>

The classes page will allow users to view the yoga studio's classes available. 
  * Each class has it's name and price clearly visible
  * There are three images displayed on the page. Giving the customer a selection of classes

  * #### Contact Page
<img src="documentation/contact-page-600.png" width="600"></p>
  
  The Contact page will allow users to fill out a clear and simple-to-use form with their information and space to add a brief message.  
  They will be required to check the terms and conditions box.
  
  There is also a section on how they came across our page, which is not a requirement to choose, but will help with our own data analysis. 
  Below the contact form is another copy of Google Map Section on where the studio is located.
  * When the user clicks the Submit button, they are brought to a Thank You page with a short message confirming their form has been received successfully.
  * 
 <img src="documentation/thankyou-page-600.png" width="600"></p>

## Future Features
  * dynamic schedule bookings
  * online yoga classes
  * audio link to work at the top of the page
  * add site name to footer
  * user's can click on the plus(+) button to drop down details of the class / session
  * facebook link in footer to function correctly 
    
## Testing
The website has been tested on Google Chrome, Safari and Firefox and all rendered successfully.

  | Action: | Expected Result: | Pass/Fail: |
  |:---|:---|:---|
   Enter URL/Click Link | Landing Page | Pass |
  | Classes Page Link | Menu Page | Pass |
  | Contact Page Link | Contact Page | Pass |
  | No 1st Name added on form | Pop up message | Pass |
  | No last Name added on form | Pop up message | Pass |
  | No email added on form | Pop up message | Pass |
  | No T's & C's checked on form | Pop up message | Pass |
  | Dropdown media list on form | List of options | Pass 
  | Click Submit | Thank You message displays | Pass |

  ## Validator Testing
  * HTML
  * 43 errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/#textarea)
![HTML Validation](<documentation/HTML Validator.png>)

  * CSS
    * 8 errors were returned when passing through the official [Jigsaw validator](https://jigsaw.w3.org/css-validator/)
![alt text](documentation/jigsaw-validation.png)

  * Lighthouse
    Lighthouse scores were high on SEO but fell short on other areas
     Lighthouse on the index.html scored the website 65 for Performance, 82 for Accessibility, 89 For best practices and 100 for SEO
    <img src="documentation/lighthouse-result-index.png" width="200"></p>
    Lighthouse on the classes.html scored the website 92 for Performance, 87 for Accessibility, 89 For best practices and 100 for SEO
    <img src="documentation/lighthouse-result-classes.png" width="200"></p>
    Lighthouse on the contact.html scored the website 93 for Performance, 85 for Accessibility, 67 For best practices and 100 for SEO
    <img src="documentation/lighthouse-result-contact.png" width="200"></p>


  * Wave
    * 3 empty headings found and 2 empty links 
    * <img src="documentation/wave-result.png"></p>
    
![alt text](documentation/wave-validation.png)

### Solved Bugs
* Footer bad accessibility
  * I put the footer into separate Div's and changed the Justify Content in the CSS to space evenly 


### Unfixed Bugs
  * Audio button on index.html does not work as expected
 

## Deployment
The Yogaworld site was deployed to GitHub pages. The steps to deploy are as follows:
1. In the GitHub repository, navigate to the Settings Tab.
2. From the source section drop-down menu, select the Master Branch.
3. Once this is selected, the page will be automatically refreshed with a detailed ribbon display to indicate successful deployment.
The live link can be found on GitHub (https://martinobodo.github.io/Project-1/index.html)
#### Local Deployment
The steps to clone this project to create a local copy are as follows:
1. In GitHub.com, go to the main page of the repository.
2. Click on the green code button.
3. Copy the URL for the repository
4. Open the terminal in the location you wish the repository to be cloned.
5. Type `git clone` and then paste the URL

## Credits
### Content
* Favicons: Created in gimp [https://www.gimp.org/downloads/]
* Google Maps: [Google Maps website](https://www.google.com/maps)
* Menu Content: [Yoga at the reach website] (https://www.yogaatthereach.com/schedule)
* C.I Love Running - Help for CSS and Git commands

### Media
* Images: [Free Images Website][(https://www.pexels.com/)
* Fonts: [Google Fonts website](https://fonts.google.com/)
* Sale Gif: [Giphy website](https://giphy.com/explore/free)
