# Kids Mini Rugby

Kids Mini Rugby is a site targeted for parents to find out about Mini Tag Rugby for juniors at their local rugby club in Guildford.  The site hopes to help users navigate what is on offer for children from the ages of 5 to 10 years old.  It will give information to parents seeking to sign up their child / children for mini tag rugby at the weekends at their local community rugby club. It will provide descriptions of the Club Officials who are volunteers and list the times and days available for the coaching sessions that are run.

It hopes to provide a friendly representation of the club by including images and videos of play and a map with directions for where the games are played.

## Features 

The website will have four navigation headings, with the About Us being embedded in the Home page following discussions with my mentor;

1. Home page
2. About Us
3. Gallery page
4. Sign Up page

![All Wireframes in pdf](https://github.com/bellsmith15/Kids-Mini-Rugby-project/blob/main/assets/readme-files/Kids-Mini-Rugy-WireFrames.pdf)

I have chosen the color schemes of red, green and an off-white for the background.  These colors compliment the images that have been used on the website. I produced wireframes on Balsamiq as an example of the pages I was considering doing. (see links below)  After my call with my mentor, they suggested that I put the "About Us" information into the home page and not on another page and instead create a link within the home page to the nav bar, which will create three pages to the site.

![Home](/assets/readme-files/wireframes/homepage-v1.png)
![Home](/assets/readme-files/wireframes/homepage-v2.png)
![About Us](/assets/readme-files/wireframes/about-us-v1.png)
![Gallery page](/assets/readme-files/wireframes/gallery-v1.png)
![Sign Up page](/assets/readme-files/wireframes/sign-up-v1.png)

After consideration and discussion with my mentor I chose to create Homepage-v2 a Gallery and Sign Up pages.  I also added a link half way down the Home page to the Sign Up page to make it easier for users to find the form to complete to join the rugby sessions.  I want my users to find a site that is easy for them to navigate around to find out information about the friendly club.  They will be able to find a brief description of each age groups activity, the times and location and a sign up form. To make the user feel inclusive about joining there are images and videos for them to familiarize themselves.

- __Navigation Bar__

  - The navigation bar will be featured on all three pages. The navigation will link to the Home page, the About Us section within the home page, the Gallery and the Sign Up page.  This will allow the users to easily navigate between each of the pages. There will be a hover activation when the user browses over the menus and a red bottom margin line indicating what current page they are on.

  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](/assets/readme-files/screenshots/nav-bar.png)

- __The Landing Page Image__

  - On the landing page the user will see a main image of two boys in a rugby tackle with a welcome message and information about what is available and images and or videos of sessions.

![Landing Page](/assets/readme-files/screenshots/landing-page.png)

- __What the club offers__

  - The club offers section will allow the user to see what is offered and the different training sessions by age group that are provided. They will see an about us section where they will be able to either view images or video under the catergories of who, what and coaching.

  - There will be navigation links to the about us and sign up in this section.

![What the club offers](/assets/readme-files/screenshots/what-we-offer.png)

- __The Footer__

  - The footer section includes contact information and links to social media sites for kids mini rugby. The links will open to a new tab to allow easy navigation for the user. There will be a Directions anchor that will take the user to the sign up page where a googlemap displays the club address.

![Footer](/assets/readme-files/screenshots/footer.png)

- __Gallery__

- The Gallery will display images of children and coaches so that the user can see what the rugby sessions are like and if they would be interested in signing up for sessions.

![Gallery](/assets/readme-files/screenshots/gallery.png)

- __The Sign Up Page__

- The sign up page will allow the users to sign their children up for a session in either the U6, U7, U8, U9 or U10 category. On landing on this page the user will need to submit their own name, their child / childrens name and an email address and any additional information they might find inmportant to advise the club.

- The page will also contain a map of where the club is in Guildford and also a brief summary about what each age group does in their rugby session.

![Sign Up](/assets/readme-files/screenshots/sign-up-page.png)

- __Additional Features__

- In the future updates to the form to include e-commerce section for making a payment for sessions either weekly monthly or for the season. It would describe the discounts you could save if the payment was in full compared to weekly. It would allow the user to sign up to the session and also pay in advance of going.  Giving a financial benefit to the club.

## Technologies Used

- HTML - was used for structuring and presenting content to the web.
- CSS - was used to style the pages.
- GitHub - was used to host the deployed website and the repository of all previous versions.
- Gitpod - was used as a cloud based environment for development.
- Font Awesome - was used to source all icon images to be used in CSS.
- Google Fonts - was used to source all fonts.
- GitHub Pages - was used to deploy the website.
- https://web.dev/measure/

## Testing 

![Responsiveness](/assets/readme-files/screenshots/am-i-responsive-test.png)

- I used the site web.dev to measure the websites performance and made improvements to HTML and CSS that improved the Accessibility ( https://web.dev/measure/ )

Insert screen shot of it here

## Tested Browsers:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

## Tested Responsiveness on:
- Laptop @ 1024px
- Tablet @ 768px
- Mobile @ 425px
- Mobile @ 375px
- Mobile @ 320px


- Bugs fixed during development through Media queries and CSS styling when testing in browsers or on inspect.  A Bug found with the images section on the home page on reviewing the web.dev was resolved with CSS container to resize the images.

- There is a known bug in the Form section. In this instance the Form is not posted to a link and has been omitted on purpose for this project and advised by my mentor to state this in the readme document.  If a user  woudl try and complete their form it would not be sent and a 501 error occurs. 

   -  https://formdump.codeinstitute.net/" IS NOT POSTED IN THIS PROJECT get 501 error - is noted on line 44 of the signup.html.

- When testing the responsiveness the navigation items appeared in the reverse order when reduced to a mobile size.  I corrected this by researching on stack over flow on how to reverse order float elements, which resolved the bug.

- In the browsers I tested that all the links worked in the pages and that the video content played ok. The website looks good on desktop and laptop and lower sizes have the images tiled on top of each other when the responsiveness is reduced. On ** browser welcome note is in the wrong position for a desktop

- Some of the confidence and values paragraphs were coming out in the incorrect places, after checking the responsiveness in each device this was resolved by entering the correct height and font values.


### Validator Testing 

- HTML
 - No errors were found when passing through the W3C HTML validation on either the home, gallery or signup pages 
  <!-- - [W3C validato - Home page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
  - [W3C validato - Gallery page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
  - [W3C validato - Sign Up page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html) -->

- CSS
  - No errors were found when passing through the W3C CSS validation on either the home, gallery or signup pages 
  
- ![CSS homepage](/assets/readme-files/validation/W3C-CSS-Validation-Service-homepage.png)

- ![CSS gallery](/assets/readme-files/validation/W3C-CSS-Validation-Service-gallery.png)

- ![CSS signup](/assets/readme-files/validation/W3C-CSS-Validation-Service-signup.png)


## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - Login to GitHub with my Username and password
  - Opened the Kids-Mini-Rugby-project repository
  - Navigate to the "Settings" tab
  - Then click on "Pages" from the "Options" menu
  - From the "Source" section, click the dropdown for "Branch" and select "Master" then hit "Save"
  - Once the Master Branch has been selected, the page will be automatically refreshed with a message advising "Your site is published at..

The live link can be found here - https://bellsmith15.github.io/Kids-Mini-Rugby-project/index.html


### Content and Media

- HTML - was used for structuring and presenting content to the web.
- CSS - was used to style the pages.
- GitHub - was used to host the deployed website and the repository of all previous versions.
- Gitpod - was used as a cloud based environment for development.
- GitHub Pages - was used to deploy the website.
- Google Fonts - was used to source all fonts.
- Font Awesome - was used to source all icon images to be used in CSS.
- Pexel - was used to source all video and images.
- Formito.com - was used to make a free favicon.


### Support

- https://w3schools.com for tips and queries when troubleshooting images, responsiveness, forms and tables
- https://stackoverflow.com for tips and queries when troubleshooting images, responsiveness, forms and tables
- http://ami.responsivedesign.is/# for testing responsiveness
- https://web.dev/measure/ for measuring the website performance
- https://extension.umaine.edu/plugged-in/technology-marketing-communications/web/tips-for-web-managers/embed-map/ for how to embed a google map
- https://imagekit.io/blog/how-to-resize-image-in-html/ for how to resize an image in HTML
- Developer Tools - inspect for troubleshooting code and bugs
- Code Institute for The Love Running Walkthrough project and essential HTML and CSS for guidance
- Support and guidance from my sessions with my mentor


### Content 

- The icons in the pages and footer were taken from [Font Awesome](https://fontawesome.com/)
- The favicon for the page was made on [Formito](https://formito.com/tools/favicon)


### Media

- The photos used on the home and sign up page are from Pexel and Videvo
- The images used for the gallery page were taken from Pexel

- The images and videos used for the web pages gallery were taken from [Pexel](https://www.pexels.com/search/rugby/) and [Videvo](https://www.videvo.net/search/rugby/)
