# DISCOVER ASIA TRAVEL AGENCY

![Responsive Mock Image of Discover Asia website](docs/responsive-mock-image.png)

Discover Asia is a travel agency website created to showcase to globetrotters and leisure travelers what this amazing agency can offer them for their next holiday trip. It desires to focus on holidaymakers who don't just want to simply travel, but to travel with convenience, style and luxury through the agency's personalized VIP services. And it aims to entice luxury travelers to choose Asia and get in touch with Discover Asia by presenting it with the utmost consideration for user experience.

<!-- Responsive Sample Image Here -->
---
## Features
---
### Existing Features

* **Navigation Bar**

    The navigation bar contains 2 main divisions of links to other pages or major sections of the website - the **logo** and the **nav menu**. This navigation bar is displayed in all pages of the website for easy and convenient routing.

    * Logo
    
        The logo, when clicked or tapped, links back to the home page. And it is created using Water Brush and Oxygen font families.

    * Nav Menu

        The nav menu is composed of links to the Home page, Destinations page, 'About Us' section, and 'Contact Us' page.

    <!-- Nav Bar Image -->

* **Home Page Banner**

    The banner in the Home page is laid out with a background image of the tranquil picture of Maldives, an autoplayed video (without audio, but with controls) of a resort along the beach, a tagline that succintly describes the company and what it does, and also a trustpilot rating to add credibility. All of these elements fused together paints a picture of a luxury travel agency with topnotch focus on details and excellence.

    * Tagline
        
        'Travel in Style, Travel Asia, Travel with Us!' tagline briefly and clearly explains the company in few words.

    * Background Image

        The picture of Maldives is chosen as background image as it represents luxury, paradise and tranquility, which is what Discover Asia is seeking to provide to all its holidaymakers.

    * Banner Video

        An audio-less autoplaying video of a resort beside the beach is added to give an extra feel of sophistication to the website. (See Accessibility section for explanation regarding the deviation to the standard rule of avoiding autoplay.)

    * Trustpilot Rating

        The display of an excellent trustpilot rating in the banner helps build confidence for the company by the clients who visit the site.

    <!-- Banner Image -->

* **'What We Offer' section**

    In this section, five (5) immensely significant and especially important services of the company are presented in a concise and easy-to-understand style by providing keywords and single-sentence explanations. And this is designed to be clutter-free and simple to keep client's focus when viewing this part.

    <!-- What We Offer Image -->

* **'Our Top Destinations' section**

    This section displays images of the six (6) most popular countries in Asia where the travel agency can bring its clients. These are the countries that clients love to visit the most. At the bottom of it is a button that links to the Destinations page for clients who are interested to see all the other countries where Discover Asia can bring them.

    <!-- Top Destinations Image -->

* **'What Our Clients Say About Us' section**

    Company reviews by clients are displayed on this part of the Home page. This adds to the company's authenticity and reliability, thus bolsters the credence of users towards the company.

    <!-- Reviews Image -->

* **'Who We Are' section**

    This section presents a description of what and where Discover Asia is, the kind of professionals behind it, what it does, and why the company exists. Its content is written simply and short to easily convey a message and so as not to be overwhelming to a reader/user. At the bottom of the section is a button which links to the Contact Us page.

    <!-- About Us Image -->

* **'Subscribe to Newsletter' section**

    In this area is situated an input field for email address for users who wish to subscribe to the company's newsletter. It also contains a heading at the top to inform users of what it is for, a clearly worded label to instruct what to do, an input field where an email address goes into, and a submit button at the bottom. 


    <!-- Newsletter Image -->

* **Footer**

    In the footer section is found Discover Asia's main office **map**, **address**, **email address**, **phone number**, **social media links**, and the **copyright**. This section is present in all pages of this website.

    * Map

        The map embedded in the footer section is from Google Maps, which allows the free use and embedment in a website. It is interactive as it can be zoomed in and out, and also it can be viewed in a larger map via its clickable link.

    * Main Office Location & Contacts

        The office address, email address, and phone number are grouped together.

    * Social Media Icons

        The social media links of Discover Asia are displayed through social media icons for Facebook, Twitter, Instagram, and Youtube. These icons when clicked or tapped will open in a separate window to prevent the disruption of browsing the main website of Discover Asia.

    * Copyright

        The copyright is located at the lowermost part of the footer. 

    <!-- Footer Image -->

* **Destinations Page**

    The Destinations Page is where all the Asian countries that the agency is bringing its clients to are shown. Sample images of each country are displayed along with a short description of what each prides itself with. With this, users will be given a snippet of idea of what each country has in store for vacationers.
    
    As of the present, there are a total of ten (10) Asian countries that are included in the list.

    <!-- Image  -->

* **Contact Us Page**

    The Contact Us Page begins with a call-to-action statement (Let's Plan Your Holiday!), followed by an instruction, and a form to be filled in.

    In the form, the user is required to provide their name, email, phone number, and destination of choice before they can submit their information. As an option, the user may also supply the time they are available to take phone calls, and a message.

    Before the form inputs can be submitted, user have to agree that a staff of the agency can contact them via the contact details they provide. This can be done by ticking the checkbox below the message field.

    <!-- Image -->

* **404 Page**

    <!-- Text -->
    <!-- Image -->

* **Contact Form Submission Feedback Page**

    <!-- Text -->
    <!-- Image -->

* **Newsletter Subscription Feedback Page**

    <!-- Text -->
    <!-- Image -->


### Features Left to Implement

<!-- Content Here  -->

---
## Testing
---
### Responsiveness

This website is made fully responsive from the largest screen to the smallest mobile screen size of 280px. 
* This was tested using the web developer tools on Chrome, Firefox, Microsoft Edge, and Safari. 
* Also, an online tool called ['Mobile-Friendly Test'](https://search.google.com/test/mobile-friendly) was used to test the site's mobile-friendliness as likely more people nowadays are using mobile devices to access the internet.
    
<!-- images -->

### Accessibility

As it is important that people with disabilities have the equal chance of using the web, this site also gives significant consideration to its accesibilitiy.

The site is made with concern for:
* Sufficient contrast between foreground and background colors,
* Distinctness of interactive elements, like links and buttons, through change of styling during mouse hover,
* Consistent placement and styles of similar links and buttons to avoid confusion and for easy navigation of the site,
* Clear association of labels to their respective input fields, such as positioning them adjacent to each other and connecting them with same IDs,
* Inclusion of immediate feedback mechanism through: 
    * Giving an immediate indication or warning, which is browser dependent, next to the input field when the form is submitted without completing the required input field. This is setup by adding the 'required' attribute in the input fields that are necessary to be filled before the form can be submitted.
    * Using a separate feedback page that will show a response when a form (e.g., contact-us form) or input field (e.g., newsletter subscription field) is successfully submitted, and
* The use of **alt** texts on images, and **aria-label** on certain links (such as the social media icons).

To ensure that most of the items mentioned above are achieved, the [WAVE - Web Accessibility Evaluation Tool](https://wave.webaim.org/) is utilized.

However, this website still allows the audio-less video displayed in the banner to autoplay. This is intentional and is part of the design of the site. It is permitted by the author to behave in this way since the video does not appear distracting, but instead possess a calming effect, and helps in creating a pleasant and stylish mood for the entire webpage. But for users to still maintain some control over their experience in the site, 'controls' for the video are kept available so users can pause or play the video as pleased by the user.

<!-- Image -->

### Links/Buttons Functionality Testing

This website successfully passed the following testing methods:
* **Manual testing** on different browsers (Chrome, Firefox, Microsoft Edge, and Safari) confirmed that all links and buttons are working as intended and redirect to the appropriate pages.

<!-- Image -->

### Validator Testing

* HTML
    * Using [W3C Markup Validator](https://validator.w3.org/), no errors were found.
* CSS
    * Using [W3C CSS Validator](https://jigsaw.w3.org/css-validator/), no errors were found.

### Fixed Bugs

* ISSUE:     
    At max-width: 1029px, the sticky 'Back to Top' link became positioned behind 'Top Destinations' images, thus concealing part of the 'Back to Top' link.

    * Intended Outcome:
        What I expect the 'Back to Top' link to do is to always stay infront of all elements so it is always 'clickable' wherever in the page it is seen.

    * SOLUTION:     
        I found out that the images were given a z-index of 1, also the texts on top of the images have z-index of 2. And so, to fix it, I gave the 'Back to Top' link a z-index of 3. So now the 'Back to Top' link is always in front of any element.

* ISSUE:    
    My images in 'Top Destinations' section had an extra (unwanted) space/gap below it despite having given the width of 100%, which I was hoping that it will fill its container.
    * SOLUTION:     
        After researching the internet for a solution, I found in Stackoverflow an explanation for it, which is a reminder that an <img> is an inline element. That being so, it sits on a line where its 'descenders', which extend below the baseline like the letters in the alphabet, will create an extra space below it. Here is the link for the Stackoverflow explanation: [Stackoverflow](https://stackoverflow.com/questions/5804256/image-inside-div-has-extra-space-below-the-image).

* ISSUE:    
    The text content in the section BUTTON moves slightly downwards and also moves the page slightly along with it during hover.

    * Intended Outcome:     
        I want the background color and text color of the button to switch and a 3px solid border to be created during hover, without affecting or changing the width and/or height of the button. Also, I do not want the button to oddly move the page even slightly when button hovered.
    * SOLUTION:     
        After realizing that a border has its own width and height, and could be the cause of increasing the lenght of the entire button during hover, I added 'box-sizing' property with the value of 'border-box' on the hovered button so the height and width of the border that is created during hover will be contained or absorbed in the width and height of the button, and not add in to it.

### Unfixed Bugs

<!-- text content -->

---
## Deployment
---

### Version Control

<!-- text content -->

### GitHub Pages Deployment
The website is published on Github Pages. The following are the steps in deploying the site:
1. Inside the Github repository of 'discover-asia', click on 'Settings' on the menu just below the respository name.
2. Then, among the options on the left sidebar, click on 'Pages'.
3. On the right side of the sidebar, look for 'Source', and under that is a dropdown menu for 'Branch'.
4. Click on the dropdown menu for Branch, and select 'main'.
5. Then, click 'Save' button. The deployed website will be 'live' after few minutes.

The live link to the Discover Asia website is found here: **[Discover Asia](https://marked-gil.github.io/discover-asia/)**.

![Github Pages Deployment Image](docs/github-deployment.png)

### Clone Repository Code

<!-- text content  -->

___
## Design Wireframes
___
The following are the schematic blueprints, or wireframes, used to build this website. And these wireframes were created using [Balsamiq](https://balsamiq.com/).

### HOME PAGE 

* Large Screens (desktops | laptops | TV screens)

![Home Page Wireframe for large screens](docs/home-large.png)

* Medium Screens (Small laptops | tablets | ipads)

![Home Page Wireframe for medium screens](docs/home-medium.png)

* Small Mobile Devices (smart phones)

![Home Page Wireframe for mobile phones](docs/home-small.png)

### DESTINATIONS PAGE

* Large Screens (desktops | laptops | TV screens)

![Destinations Page Wireframe for large screens](docs/destinations-large.png)

* Medium Screens (Small laptops | tablets | ipads)

![Destinations Page Wireframe for medium screens](docs/destinations-medium.png)

* Small Mobile Devices (smart phones)

![Destinations Page wireframe for small screens](docs/destinations-small.png)

### CONTACT US PAGE

!['Contact Us' wireframe](docs/contact-form.png)

### CONTACT FORM FEEDBACK PAGE

![Contact form submission feedback wireframe](docs/contact-feedback.png)

### NEWSLETTER FEEDBACK PAGE

![Newsletter feedback wireframe](docs/newsletter-feedback.png)

### PAGE NOT FOUND PAGE (404)

![404 feedback wireframe](docs/404-wireframe.png)

___
## Technologies
___

This website uses the following technologies:

* **Languages:**    
    This website is created using only 2 languages:
    * **HTML** - or *'Hypertext Markup Language'*, is used to build the structure of the web page while utilizing its semantic elements.

    * **CSS** - or *Casscading Style Sheets*, is used to style the look or presentation of the webpage. Layout methods such as Flexbox and Grid layout are utilized.

* **Gitpod**.  
    Gitpod is the cloud-based IDE (Integrated Developer Environment) used to build this site.

* **Git**  
    Git, as a version control system, is made use of to monitor and record changes made when building the site. This allows for the restoration of an earlier version of the code should it be necessary.

* **GitHub**    
    The created source code to build this website is stored in GitHub as a repository.

* **GitHub Pages**  
    The website is hosted live in the web through GitHub Pages, which is a hosting site for static web pages, via GitHub.

* **Favicon.io**    
    Favicon is the icon displayed beside the site title, usually seen in the browser tab. The customized favicon used in this website is from [Favicon.io](https://favicon.io/).

* **Balsalmiq**     
    Generating the structure of the design concept was done with wireframes from [Balsalmiq](https://balsamiq.com/).

* **Tinypng**
    To improve the performance of the site, the images were compressed through [TinyPNG](https://tinypng.com) to reduce their file size.

* **Convertio**
    * To convert jpeg images to webp format files, [Covertio](https://convertio.co/jpg-webp/) was used.

---
## Credits
---
### Content

* **Texts**     
    The text contents of the website are originally written for the site by me - the creator.   

    For the DESTINATION page's main content (such as the description for each country) to be factual, I have researched on multiple sites, especially travel websites, where I based most of the texts from.
    
* **References: Go-to Sites for CSS & HTML**    
    My main reference for learning and reviewing CSS and HTML are:
    * [W3schools](https://www.w3schools.com/), 
    * [MDN](https://developer.mozilla.org/en-US/), and 
    * [Code Institute's](https://codeinstitute.net/ie/) lectures.   

* **'Responsive Web Design with HTML5 and CSS by Ben Frain'** Book

    The idea on how to keep the footer at the bottom edge of the viewport (i.e. when there is no sufficient main content to push the footer at the endmost part) is from this book of Ben Frain. This is useful on the 'form submission feedback' page and the 'subscription feedback' page where the contents do not always have enough height, especially on large screens, to stick the footer at the bottommost part. (See solution and explanation on the **'Fixed Bugs'** section).
    
### Media

* Images
    * All the pictures displayed on the website are taken from free stock photography websites. Most are from [Pexels](https://www.pexels.com/), a few are from [Pixabay](https://pixabay.com/), and the banner background image is a photo by 'yang wewe' from [Unsplash](https://unsplash.com/).

* Video
    * The video displayed in the banner is taken from [Pexels](https://www.pexels.com/).

* [Google Map](https://google-map-generator.com/)
    * The map used in the footer section is generated using **Google Map**.