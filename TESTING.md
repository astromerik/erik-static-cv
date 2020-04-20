<div align="center">

[View this website on GitHub Pages](https://astromerik.github.io/erik-static-cv/) 
</div>

## Testing 

### Validation 

As mentioned in the [README.md](assets/README.md) the [W3C's HTLM Validator](https://validator.w3.org/) and [W3C's CSS Validator](https://validator.w3.org/) were used to validate the websites HTML and CSS code.
As of date the code get no error or warning messages when running through the validators. 

### Testing function by function 

#### Navigation bar 

* The navigation bar is clickable and each button in the navbar is highlighted when the mouse hover over them. 
* When clicked - "Home" takes the user to the Home section
* When clicked - "About" takes the user to the About section
* When clicked - "Skills" takes the user to the Skills section
* When clicked - "Projects" takes the user to the Projects section
* When clicked - "Contact" takes the user to the Contact section
* When clicked - The logotype in the left corner takes the user to the Home section

* When the width of the screen is less than 768 pixels, the navbar collapses into to a "hamburger menu". 
* When the "hamburger" button is clicked - the navbar with the section options appear. 
* When clicked in the appeared hamburger menu - "Home" takes the user to the Home section
* When clicked in the appeared hamburger menu - "About" takes the user to the About section
* When clicked in the appeared hamburger menu - "Skills" takes the user to the Skills section
* When clicked in the appeared hamburger menu - "Projects" takes the user to the Projects section
* When clicked in the appeared hamburger menu - "Contact" takes the user to the Contact section
* When clicked - The logotype in the left corner takes the user to the Home section

* The hamburger menu does not dissapear (as expected) when a section is clicked. This requires JavaScript and will be added in future stage. 

#### Footer

* The footer is responsive and the margin between the icons is reduced along with the width of the screen is reduced. 
* When clicked - The Twitter icon opens a new tab in the browser and take the user to Erik's Twitter page 
* When clicked - The LinkedIn icon opens a new tab in the browser and take the user to Erik's LinkedIn page 
* When clicked - The GitHub icon opens a new tab in the browser and take the user to Erik's GitHub page 
* When clicked - The Slack icon opens a new tab in the browser and take the user to Slacks main page

#### Home section

* The home section have no clickable functions. 
* When the width of the screen is less than 375 pixels, the margin of the icons beneth the profile pictures changes to fit the small screen. 

#### About Section 

* The timeline in the about section is responsive over all sizes. When reaching a smaller screen width, some headings stack their words on top of each other, and the dots on the timeline follows. 
* When the "download CV" icon on the bottom of the section is clicked, a new tab in the browser is opened and takes the user to the full CV. 

#### Skills 

* The skill sections two boxes, "What can i do?" and "What is good UX to me?" is stacked on top of each other when the screen width is less than 768 pixels. 
* Both the progress bars and the text box is responsive and on a width of less than 768 pixels, they take up the full width of the screen. 
* The progress bar have clickable icons for respective language/technology and when clicked:

* The HTML icon opens a new tab in the browser and takes the user to the HTML Wikipedia page
* The CSS icon opens a new tab in the browser and takes the user to the CSS Wikipedia page
* The JavaScript icon opens a new tab in the browser and takes the user to the JavaScript Wikipedia page
* The Python icon opens a new tab in the browser and takes the user to the HTML Python page
* The Swift icon opens a new tab in the browser and takes the user to the HTML Swift page

#### Projects 

* The project section contains three clickable projects. 
* Both the images and the text beneath the images are clickable. 
* When the specific project is clicked, a modal pops up. 
* When the modals button "View code" is clicked, a new tab in the browser is opened and the user is directed to the repository of the project. 
* When the modals button "close" is clicked, the modal is closed. 
* When the user click outside the modal, the modal is closed. 
* The above functionality work for all three projects. 

* The projects images are displayed horisontally on larger screens, but stacked on top of each other when the screen width is less than 768 pixels. 
* The project images sizes are responsive and changes along with the screen width. 
* The GitHub icon on the bottom of the page is clickable and when clicked, a new tab in the browser opens and the user is diracted to Eriks github page (showing all repositories).

#### Contact 

* The contact form is responsive and will at all times take up 75% width of its container. 
* The contact form will not be sumbitted if the "Name" and "Email" is empty. If the submit button is clicked when these parts are empty, a pop up with the text "Please fill in this field" will show for the two parts. 

### Webpage on different browsers/devices 

* The website's functionality is working and is identical on Google Chrome, Mozilla Firefox, Safari and Microsoft Edge. On Internet Explorer the functionality is more unstable and is working as it should 9 out of 10 times when tested. This require more investigation. 
* When using the browsers developer tools, the functionality for the different mobile devices are working as expected. However, when using the website on a iPhone in reality, the hamburger button is reduced from 3 to 2 stripes. This phenomenon does not appear on OnePlus 7T or Huwaei P30 Pro. More investigation is required. 
 

 ### Future testing 
 * As new functions are added, new testing will be completed. 