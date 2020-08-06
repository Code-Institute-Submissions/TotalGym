
[![alt text](/assets/images/TotalGymLogo_small.png "Click to open site")](https://phil-griffith.github.io/TotalGym/)

![alt text](/assets/images/responsive.jpg "Responsive demo")

This website has been created for a fictional Gym based in Buckinghamshire called Total Gym. The core ethos of Total Gym is to be more than just a place to exercise, it aims to provide a total health and fitness solution by providing services that cater for all areas of health and fitness. The Gym is currently independent but the owners are intending to franchise in the future if Total Gym is a success.
___

## UX

### User Stories

As the owner of the Total Gym website I would like:
- To inform new customers about everything Total Gym has to offer.
- To provide a facility for customers to make enquiries via the website.
- To give new and existing members information about our classes and class times.

As a user I would like:
- To find out what facilities and services are available.
- To find out how much the membership costs.
- To be able to check class times.

&nbsp;

### Design
- #### Wireframes
  The website was initially designed using Balsamiq to create several wireframes (link below).
\
\
[Wireframes](/assets/wireframes/wireframes.md)

- #### Typography
  The majority of the text has been styled with the 'Krona one' font as this gives a strong and bold impact. The Roboto font was used in other areas for clarity and ease of reading.

- #### Colours
  The following colours have been used for this site:
    - Black - page backgrounds, Navigation Bar and Footer.
    - Green - Total Gym logo background, buttons, Class Timetable and Navigation Bar hover and active page effects and Footer hover effects.
    - White - Total Gym logo text, site text and borders.

- #### Code Rationale
    After deciding to use Modals for the forms, it became apparent that the code would need to be duplicated on every page to have the buttons available on every page. HTML templates were considered as a way of preventing the code duplication, but this would have required additional JavaScript code. Therefore, the decision was made to duplicate the code and add comments to make it clear that the code is duplicated on the other pages.

___

## Features

### Existing Features
- Navigation Bar contains links to all site pages and is featured on every page.
- Tell Me More button opens a modal form to request more information and is included on every page.
- Join Now button opens a modal form to join Total Gym and is included on every page.
- Clickable images on the CLASSES and FACILITIES pages that open modals containing further information.
- A scrollable Class Timetable is included on the CLASSES page.
- The site Footer for all pages contains social media links.
- Site is fully responsive for all screen sizes.

&nbsp;

### Features Left to Implement
Members area containing the following:
  - Activity tracker
  - Diet plan/tracker
  - Workout plan
  - Discounted in house products
  - Home workout videos

___

## Technologies Used

### Languages

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks and Programs

- [Bootstrap 4.5.0](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
  - Many features of Bootstrap were used to make the site responsive.
- [JQuery](https://jquery.com)
    - Used to implement some of the Bootstrap features such as NavBar and Modals.
- [Atom](https://atom.io/)
  - This site was built using the Atom IDE.
- [Balsamiq](https://balsamiq.com/)
  - Wireframes were created in Balsamiq.
- [GitHub:](https://github.com/)
    - The GitHub package within Atom was used to manage version control and Push content to the repository.
- [RealFaviconGenerator](https://realfavicongenerator.net/)
  - Used to create the favicon.
- [CSS Autoprefixer](https://autoprefixer.github.io/)
  - All CSS code was checked to ensure compatibility with multiple browsers.

___

## Testing

### Pre-Deployment
Throughout the development of this site, it was previewed locally as each new element was added, and also, the built-in browser developer tools for Chrome, Edge, Safari and Firefox were used to ensure that the layout was responsive for all screen sizes.

&nbsp;

### Post-Deployment
Once the main structure of the site was complete it was deployed to GitHub Pages to test it on actual devices. This revealed some behaviour that had not been seen when using the developer tools responsive utility, such as, hover effects appearing when touching images on mobile devices.

&nbsp;

### Issues found and fixed
- Class Timetable formatting - Due to the use of sticky cells, when the screen is resized some cells disappear under the sticky cells. This was resolved by using CSS media queries for all known screen sizes.
- Image Hover effects appearing and persisting after touching images on touchscreen devices. Resolved by removing Hover effects for screen sizes of 1024px and below.

&nbsp;

### Final checks

The final checks included:

- #### Code Validation
  - [W3 HTML validator](https://validator.w3.org/#validate_by_input)
    - All HTML code was checked and any errors found were fixed.
  - [W3 CSS validator (jigsaw)](https://jigsaw.w3.org/css-validator/#validate_by_input)
    - CSS code was checked and no errors were found.

- #### Feature testing
  The following items were checked and verified:
  - ##### Navigation Bar page links
    The Navigation links were tested for the following; hover effect to ensure that the colour changes to green, current active page link is coloured green and that each link opens the correct page.

    &nbsp;

    <img src="/assets/images/navbar.jpg" width="450" alt="Navigation Bar">

    &nbsp;

  - ##### Social media links

    On every page of the site, each Social Media icon was tested for hover effect and clicked to ensure that a new tab opened with the corresponding Social Media website.

    &nbsp;

    <img src="/assets/images/social_links.jpg" width="250" alt="Social Media Links">

    &nbsp;

  - ##### Form buttons and form data input behaviour

    Both form Buttons were clicked on every page to ensure that the form modals opened correctly. And the forms were tested for data validation and successful submission.

    &nbsp;

    <img src="/assets/images/tell_me_more_form.jpg" width="400" alt="Tell Me More Form">
    <img src="/assets/images/join_now_form.jpg" width="400" alt="Join Now Form">  

    &nbsp;

    ###### Input Required Validation check

    &nbsp;

    <img src="/assets/images/info_request_submit_fail.jpg" width="400" alt="Tell Me More Validation check">
    <img src="/assets/images/join_now_form_fail.jpg" width="400" alt="Join Now More Form Validation check">

    &nbsp;

    ###### Successful Submission test

    &nbsp;

    <img src="/assets/images/more_info_confirmed.jpg" width="400" alt="Tell Me More Submission">
    <img src="/assets/images/joining_confirmation.jpg" width="400" alt="Join Now More Form Submission">

    &nbsp;

  - ##### Clickable images.

    Every image on the Classes and Facilities pages was tested for hover effect and modal popup when clicked. The close buttons and close (X) icons were also tested for every modal.

    &nbsp;

    ###### Hover effect
    <img src="/assets/images/cardio_hover.jpg" width="400" alt="Cardio Image Hover effect">  

    ###### Modal Popup
    <img src="/assets/images/cardio_modal.jpg" width="400" alt="Cardio Modal popup">

    &nbsp;

  - ##### Class Timetable

    The Class Timetable was tested to ensure that the scroll function enabled full visibility of the timetable. Further testing was also conducted on multiple screen sizes to ensure that the timetable maintained usability.

    &nbsp;

    <img src="/assets/images/class_timetable.jpg" width="700" alt="Class Timetable">

     &nbsp;
- #### Responsive / Device testing
  The following devices were used to test the site:
    - 24" Monitor
    - 15.6" Laptop Display
    - 10" Galaxy Tab 4.0 (Portrait and Landscape)
    - 5.8" Samsung S8 (Portrait and Landscape)
    - 4.7" iPhone 8 (Portrait and Landscape)

    &nbsp;

- #### User Stories check

  Does this website successfully fulfil the requirements laid out in the original User Stories?

  The site owner requirements
  - To inform new customers about everything Total Gym has to offer.
    - Yes - All of the facilities and Services have been detailed on the website.
  - To provide a facility for customers to make enquiries via the website.
    - Yes - The 'Tell Me More' button (featured on every page) enables users to open a form to request more information.
  - To give new and existing members information about our classes and class times.
    - Yes - The Classes page contains details about all of the classes and includes a class Timetable for users to check class times.

  The user requirements
  - To find out what facilities and services are available.
    - Yes - All available facilities and services are included on the Facilities and Services pages.
  - To find out how much the membership costs.
    - Yes - The 'Tell Me More' button can be used for information requests of this nature.
  - To be able to check class times.
    - Yes - Class times are detailed in the Class Timetable.

    &nbsp;

___

## Deployment

The site was deployed to GitHub pages by following the below steps:
- Log in to the repository - https://github.com/phil-griffith/TotalGym/
- Click <b>Settings</b>
- Scroll down to <b>GitHub Pages</b>
- Set Source to <b>Branch:master</b>
- Click <b>Save</b>

&nbsp;

___

## Credits

### Content
Some of the content for this website was taken from the following sources:
- The text for the Yoga Modal
  - [NHS.uk](https://www.nhs.uk/live-well/exercise/guide-to-yoga/)
- The text for the HIIT Modal
  - [Wikipedia](https://en.wikipedia.org/wiki/High-intensity_interval_training)
- The text for the Boxercise Modal
  - [Wikipedia](https://en.wikipedia.org/wiki/Boxercise)
- The text for the Pilates Modal
  - [NHS.uk](https://www.nhs.uk/live-well/exercise/guide-to-pilates/)
- The text for the Spin Modal
  - [cyclingweekly.com](https://www.cyclingweekly.com/fitness/spin-classes-fad-or-fab-36077#:~:text=A%20spin%20class%20is%20a,pressure%20to%20slow%20them%20down.)
- The text for the Aqua Modal
  - [everyoneactive.com](https://www.everyoneactive.com/content-hub/fitness/aqua-aerobics-classes/)
- The text for the Free Weights Modal
  - [totalfitness.co.uk](https://www.totalfitness.co.uk/facilities-pages/free-weights-area/)

&nbsp;

### Code
Some of the code for this website was taken from the following sources:
- Navigation Bar
  - https://getbootstrap.com/docs/4.5/components/navbar/
- Carousel for Member Comments
  - https://getbootstrap.com/docs/4.5/components/carousel/
  - https://stackoverflow.com/questions/46249541/change-arrow-colors-in-bootstraps-carousel
- All Modals
  - https://getbootstrap.com/docs/4.5/components/modal/
- Cards  
  - https://getbootstrap.com/docs/4.5/components/card/
- Image Hover overlay
  - https://www.w3schools.com/howto/howto_css_image_overlay.asp

&nbsp;

### Media
The images for this website were taken from the following sources:

- #### Home Page
  - Hero
    - [active.com](https://www.active.com/fitness/articles/11-mistakes-personal-trainers-wish-you-d-stop-making/slide-4)
  - About section > Balanced
    - [ambientclock.com](https://ambientclock.com/weight-problems-issues-and-weight-reduction-physical-exercise-a-well-balanced-diet-along-with-a-health-diet.html)
  - About section > Strength Training
    - [onholdinc.com](https://www.onholdinc.com/mohblog/the-number-1-complaint-gyms-fitness-centers-smell/)
  - Member Comments section > Member 1 (Jake)
    - [shutterstock.com](https://www.shutterstock.com/image-photo/smiling-business-man-isolated-over-white-538455127)
  - Member Comments section > Member 2 (Sarah)
    - [stockfresh.com](https://stockfresh.com/image/7707601/young-pretty-blonde-hair-woman-happy-smiling-isolated-on-white-background-lifestyle-people-concept)
  - Member Comments section > Member 3 (Steve)   
    - [shutterstock.com](https://www.shutterstock.com/image-photo/young-handsome-man-black-suit-glasses-84365338)

- #### Facilities Page
  - Cardio  
    - [tripadvisor.co.uk](https://www.tripadvisor.co.uk/LocationPhotoDirectLink-g1930080-d192027-i272101321-Village_Hotel_Nottingham-Chilwell_Nottinghamshire_England.html)
  - Free Weights  
    - [google.com](https://lh3.googleusercontent.com/proxy/nFx24NYiOZMNkaelGstTFpKfzLxuQmcdkyCg8H2ZmP9aVo_2elK-3LtrVri-yp1uSIZt87QEVyHgYVJcPU5bWOVuKSMuY5ertsVrgK0dW6XGaA)
  - Weight Machines
    - [tripadvisor.co.uk](https://www.tripadvisor.com/LocationPhotoDirectLink-g187049-d191626-i272112273-Village_Hotel_Swindon-Swindon_Wiltshire_England.html)
  - Studio
    - [google.co.uk](https://www.google.co.uk/url?sa=i&url=https%3A%2F%2Fwww.nuffieldhealth.com%2Fgyms%2Fpreston&psig=AOvVaw3Y88Ydszp6ydYI2nRX7BbC&ust=1596459760086000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCJCmk5nK_OoCFQAAAAAdAAAAABAD)
   - Refreshments
     - [flamingo-freshfood.de](http://flamingo-freshfood.de/?lang=en)
   - Pool & Spa  
     - [runnymedehotel.com](https://www.runnymedehotel.com/spa/our-spa/)

- #### Classes Page
  - Yoga
    - [drbrighten.com](https://drbrighten.com/yoga-pose-warrior-i-virabhadrasana-i/)
   - HIIT
     - [theteenagertoday.com](http://theteenagertoday.com/aerobics-complete-body-workout/)
   - Boxercise
     - [sports-insight.co.uk](https://www.sports-insight.co.uk/trends-features/boxercise-adrian-hill-talks-to-a-pair-of-instructors-who-share-a-passion-fo)
   - Pilates
     - [miriamvadillo.com](http://miriamvadillo.com/classes/group-pilates/)
   - Spin
     - [pinterest.co.uk](https://www.pinterest.co.uk/pin/351703052142548374/)
   - Aqua
     - [exercise.co.uk](https://www.exercise.co.uk/learn/exercise-for-everybody-water-aqua-aerobics/)

- #### Services Page
  - Personal Trainer
      - [menshealth.com](https://www.menshealth.com/nl/fitness/a28377685/personal-trainers-delen-wat-je-over-fitgoals-moet-weten/)
  - Physiotherapy
    - [chi.ac.uk](https://www.chi.ac.uk/chichester-institute-sport/our-courses/undergraduate/bsc-hons-physiotherapy)
  - Nutritional Adviser
    - [punjabkesari.in](https://www.punjabkesari.in/education-and-jobs/news/food-nutritionist-will-get-his-career-opportunities-to-move-forward-1034000)

&nbsp;

### Acknowledgements
I would like to thank my Mentor Aaron Sinnott for the advice that he has given me.
- I received inspiration for this project from:
  - https://activ8fitnessclubs.co.uk/
  - https://www.nuffieldhealth.com/
