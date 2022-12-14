# FIRST MILESTONE PROJECT DRONEX 

## User Experience (UX)

### Initial Discussion

 The goal of the DroneX project is to create a fictional drone delivery service website. Here businesses can cooperate with us to use our company drones and revolutionise their delivery service. The goal of this website is to give  our users a clear understanding of what our service is and what it does. My goal is to generate as many new clients as possible for our service.

 #### Key information for the site:

 * DroneX is a drone delivery service.
 * We provide drones to businesses.
 * A way for businesses to expand via delivery of goods.
 * The quickest, direct, straight-to-window/balcony delivery of goods up to 12kg.

### User Stories

The purposes of various visitors of this website will vary, however, those only include the main priority of each type of visitor. For example, a business owner also must be able to easily navigate around the website, however, their priority would be to find an easy way to contact DroneX.

* As a business owner, I want to be able to find out more about DroneX to find out how they can help me to scale the delivery service of my own business i.e. deliver my goods in a faster and more efficient way.

* As a business owner, I want to be able to contact the company efficiently, which includes a contact number, email address, and physical address. 

* As a customer, I want to find out where (location, city etc.) is DroneX available.

* As a visitor, I want to be able to easily navigate around the website, read about the company and contact them with regards to any query if necessary.

### User Goals

#### Client Goals:

* The ability to view the website on various devices of different widths
* To make the site understandable for first-time users and to make the purpose clear.
* To provide clear and easy-to-notice contact information, including address.
* To make the content easy to read and accessible to all visitors.

#### First-Time Visitor Goals:

* To find out what DroneX is.
* To be able to easily navigate through the website on various devices.
* To visit our social media pages.

#### Returning Visitor Goals:

* Fill out the contact form and get in touch with us regarding doing business together.
* To start collaboration and answer any questions potential clients may have.

#### Frequent Visitor Goals:

* Our frequent visitors should be our business partners.

- - -

## Design

### Colour Scheme

 The website mainly follows a black & white scheme with a shade of lighter black.
* #fff
* #020202a1
* #707473e2
* #000000

### Typography 

Google Fonts was used for the following fonts:

* Exo with sans serif as a fallback (all text).

### imagery

All images were taken from the pexels.com website and reference was provided where applicable.

### Wireframes

Wireframes were created for desktop view. Sign Up page was reconsidered and therefore, removed
from the website.

[Home Page Wireframe](docs/wireframe-homepage.jpg)

[About Page Wireframe](docs/wireframe-about.jpg)

[Contact Page Wireframe](docs/wireframe-contact.jpg)

[Sign Up Page Wireframe](docs/wireframe-signup.jpg)

### Features

The website consists of four pages. Home page, about page, and contact page (accessible from the navbar). The only page that is not accessible from the navbar is the confirmation page which appears after a user clicked the "submit" button on the contact page form element.

* All pages on the website have:

  * A responsive navigation bar is situated at the top of the webpage. The navbar consists of a logo (DroneX, not visible via mobile view to avoid clutter, thus improving the UX) and three anchor links (home, about, and contact). Additionally, on the mobile view, the anchor links are centred as opposed to floating left. This has been done to fill the blank space on the top of the page, improve page symmetry, and make the navbar look more organised.

  * A footer that contains social media icon links to Instagram, Facebook, and Twitter. The footer also contains the locations column, and contact column (address, phone number, and email).

* Home Page

  * Background image section

   From the top, the homepage has a background image section that covers the navbar and is visible across the whole page (height 100vh on a desktop and 70vh on a mobile). The background image also has a paragraph, a heading, and an anchor link leading to the contact page.

  * Our locations section

  This section presents our current offices in a 3-column layout showcasing images (hidden on mobile and tablet), headings, and a short paragraph. 

* About Page

  * Background image section 

    With the same view height parameters as the home page. The background image also covers the navbar and has one heading. 

  * Content section
    
    The content section has a heading on the top of the section and three short gray (#707473e2) paragraphs explaining the business below.

* Contact Page

  * Background image section

    The background image also covers the navbar and has one heading and two paragraphs of text.
  
  * Form section

    The contact form requires the user to submit their email, first name, last name, company name, industry, country, agree to the terms of service and click the submit button that leads to the confirmation page. The form is styled using the bootstrap v5.2 framework and a border surrounding it. Above the contact form, there is a heading directing users to fill out the form.

* Confirmation Page

  * Thank you message section
    
    This section only contains a check icon, a "thank you" heading and a small paragraph to reassure the user that the form has been processed successfully and that we will contact the user back shortly. 

* Future Implementations
  * A JavaScript function that lets the user return to the back of the page with one click.
  * A section with success stories of our business partners with images, a heading and description.
  * Create a section that would showcase the vision for the future of the company.

### Accessibility 

It was ensured that the website is accessible and as user-friendly as possible. I have achieved this by: 

* Using semantic HTML.
* Using descriptive alt attributes on images on the site.
* Ensured that there is a sufficient colour contrast throughout the site. 
* Ensured that all my links have descriptive names. 

- - -

## Technology

### Languages Used

 HTML and CSS were used for this project.

### Frameworks, Libraries & Programs Used

* Balsamiq - Wireframes.

* Git - Version control.

* GitHub - To save and store the files for the website.

* Bootstrap v5.2 - a framework used for the website. Used when creating rows and columns. Also, the form element was almost entirely created using this framework, with the support of standard CSS3 code to override certain styles.

* Google Fonts - To import the fonts used on the website.

* Font Awesome - For the iconography on the website.

* Google Dev Tools - Troubleshooting, testing features and solving issues with responsiveness and styling.

* [Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.
* [Favicon.io](https://favicon.io/) To create favicon.

- - -

## Testing

Testing progressed at every stage of this project. This ensured that most issues were fixed before the website was finished. Chrome DevTools were utilised when building the website to help with troubleshooting as the website transformed. 

The following issues were raised during my project meeting with my mentor:

* The heading on the about.html page exceeded the width of the website, causing overscroll. This has been fixed by removing the "row" bootstrap class from the heading.
* Rather than defining padding, margin etc. in pixels, it was preferred to define them in percentage (%).
* To limit the use of Ids, use classes instead.  
* To always keep one space below and above the CSS selector.
* To add an anchor tag to the logo in the navbar so it leads back to the homepage.
* To create a confirmation page when the "submit" button is clicked on the form element.
* To format the document using shift + alt + F command.

### W3C Validator

The W3C validator was used to validate the HTML and CSS pages.

* [The HTML Home page](docs/W3C-validator-index.html.jpg)
* [The About us page](docs/W3C-validator-about.html.jpg)
* [The Contact page](docs/W3C-validator-contact.html.jpg)
* [The Confirmation page](docs/W3C-validator-confirmation.html.jpg)
* [The style.css CSS file](docs/W3C-validator-css.jpg)

### Fixed Bugs

1. The navbar kept its float: left position on mobile devices despite different intentions. The navbar was supposed to be equally centred on the mobile device, this was fixed using the justify-content: center declaration.  

2. The images in the "Our Locations" sections would not align symmetrically and their position was uneven. This was fixed using 3 declarations: display: flex, align-content: center, and justify-content: center as well as other declarations in the location-images CSS class.

3. The "Request delivery" button did not appear at all on mobile devices. This was fixed using media queries. More specifically, using position: absolute and bottom: 45% CSS declarations. 

4. The position of all headings on the background images was altered significantly when using the website on a mobile device. This was fixed using the position: absolute and other relevant declarations associated with positioning an element. 

5. The navbar anchor tags had a visible background when hovering. This issue was easily fixed using the background: none declaration.


### Test Cases

I have fully tested the website using Google Chrome and Mozilla Firefox on desktop (HP Pavilion Convertible 14 inch) and mobile (Samsung Note9). 

It was ensured that through the testing process content was responsive using the Google Developer Tools. 

#### Home page

* I began by clicking on the "home" link and the logo to see if the homepage loads correctly.
* Next, I clicked on the "Request Delivery" button to see if it leads to the contact page without errors.
* Next, I scrolled down to see if the 3 images and all content in the "Our Locations" section load correctly.
* I also checked if the anchor link works in the "Warsaw" description - The Palace of culture link to the Wikipedia page.
* I also ensured that from the Home page - all navbar links lead to the right page.
* Lastly, I checked if the social links in the footer element work correctly as well.

#### About page

* I began my testing by clicking on the "About" navbar link to see if the page and its content load correctly.
* If the page and its content load correctly, I continued to check the footer element to see if the social links work as well.
* I also ensured that from the About page - all navbar links lead to the right page.

#### Contact page

* I began my testing by clicking on the "Contact" navbar link to see if the page and its content load correctly.
* I also ensured that from the Contact page - all navbar links lead to the right page.
* Form
  * I clicked on the "Submit" button - Error message appeared "Please fill in this field" - As expected.
  * Next, I filled in the required field (email) - The same error message should appear indicating that the "First name" field must be completed before submitting the form.
  * The same process was repeated for the Last Name, Company name, Industry, and Agree to terms & conditions fields.
  * When all fields are completed, the "Submit" button should direct the user to the "confirmation.html" page displaying a "thank you" message without any errors on the form.

### Supported Screens and Browsers

* Browsers - It is recommended that you use the latest version of one of the following:

  * [Apple Safari](https://www.apple.com/safari/)
  * [Google Chrome](https://www.google.com/chrome/)
  * [Microsoft Edge](https://www.microsoft.com/en-us/edge?form=MA13FJ)
  * [Mozilla Firefox](https://www.mozilla.org/pl/firefox/)

* Screens

  * This website is suitable for mobile devices including Samsung and iPhone (Devices of the same width are also suitable).
  * Tablets.
  * Desktops.

- - -

## Deployment & Local Development

### Deployment

GitHub Pages was used to deploy the live website. Instructions:

1. Log in (or sign up) to Github.
2. Find the repository for this project, "First-milestone-project-DroneX".
3. Click on the Settings link.
4. Click on the Pages link in the left-hand side navigation bar.
5. In the Source section, choose main from the drop-down select branch menu. Select Root from the drop-down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

#### How to Fork

Fork the DroneX repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, adampl12/First-milestone-project-DroneX.
3. Click the Fork button in the top right corner.

#### How to Clone

Clone the First-milestone-project-DroneX repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, adampl12/First-milestone-project-DroneX.
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

- - -

## Credits

### Background Images

* [Home page background image](https://www.pexels.com/pl-pl/zdjecie/latanie-urzadzenie-glebia-pola-gadzet-9977848/) - Omar Ramadan

* [About page background image](https://www.pexels.com/pl-pl/zdjecie/latanie-ruch-martwa-natura-dron-9443061/) - Simon 

* [Contact page background image](https://www.pexels.com/pl-pl/zdjecie/latanie-martwa-natura-dji-kamera-drone-9739244/) - Michael Meyer

### Images on Index.html

* [Warsaw Image](https://www.pexels.com/pl-pl/zdjecie/budynki-miasto-miejski-panorama-10676/) - Skitterphoto

* [Hong Kong Image](https://www.pexels.com/pl-pl/zdjecie/miasto-budynki-port-drapacze-chmur-11451098/) - SodaTheCat

* [Singapore Image](https://www.pexels.com/pl-pl/zdjecie/gardens-by-the-bay-singapur-1842332/) - Timo Volz

### Code Credits

* [Web Master](https://www.youtube.com/watch?v=ZotQNKyvZsw) - Background Image + navbar inspiration code.
* [Janith](https://stackoverflow.com/questions/53388003/select-country-dropdown-in-html-page) - The form select country list.

- - -

## Acknowledgements

* [Rohit Sharma](https://github.com/rohit0286) - My Code Institute mentor.
* [Drone dji](https://www.dji.com/uk) - For project inspiration.
* [Kera Cudmore](https://github.com/kera-cudmore) - For sharing her readme.md with CI students.
* [Aleksandra Cyran](https://www.linkedin.com/in/acyran/) - For helping me spot any bugs.
