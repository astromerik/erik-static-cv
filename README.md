<h1 align="center">

<a href="https://astromerik.github.io/milestone1/" target="_blank"> <img src="assets/images/milestonelogo1.png" alt="Erik logo"></a>  
</h1>

<div align="center">

[View this website on GitHub Pages](https://astromerik.github.io/milestone1/) 
</div>

A portfolio website whit focus on good UX design. 
The website, which is a single page website includes a welcome section, an about section, an skills section, an project section and a contact section. 

The main purpose of this website is threefolded. 
Firstly, since the webpage is a portfolio/resume page I wanted it to reflect my personality and my idea of good UX. In other words, a website that I would like to spend some time on. 
It should be easy for me to handle contact information from users who want to come in contact with me. 
Secondly, the website is mainly aimed towards recruiters and potential employers, thus, the web site must be intuitive and easy to navigate through. 
It should provide all the neccesary information to understand what I can accomplish and how I am as a developer. 
Lastly, This wep page is supposed to develop along with me. 
This means that it will be written in clean code, available for additional languages to be inserted (for example JavaScript). 
This also means that the content on the page prefferably will be scaled downed to provide a clean look and also be more easely maintained in future development/changes. 


The developers goal of this website are:
* Branding himself
* Show what he think is good UX
* Create a interest for visitors to work with him
* Recieve project/job proposals 

The visitors goal of this website are:
* Find a skilled software developer
* Find proof of concepts (i.e. proof of programming skills)
* Easily get in contact with the developer if they are interested

## UX

#### Ideal visitors are:
* English speaking
* Working for a company who are looking to hire front end developer(s)
and/or
* Is a recruiter


#### Visitors are searching for:
* A skilled software developer
* Proof of concepts, i.e, projects/source code

#### This website make it easy for the visitor to evaluate me (Erik) because: 
* The website is intuitive and easy to navigate
* The website provides enough information for the visitor to know if they are intreseted of me as a developer
* It links to my other projects 
* It is easy to contact me through email or social media 


#### User stories
1. As a new visitor to the website, I want it to be easy to navigate through the website 
2. As a new visitor, I want it to be easy to contact Erik 
3. As a returning visitor to the website, I want news regarding Erik's employement and projects  
4. As a recruiter without technological/programming knowledge, I want to get a high level picture of Erik's background, personality and knowledge
5. As a recruiter with technological/programming knowledge, I want proof of concept, thus, access to the source code
6. As a potential employer, I want a deeper understanding of what Erik can contribute to my business with (both in terms of personallity and skills)
7. As a recruiter or potential employer, I want to know what Erik believe is good UX design

#### Balsamiq mockups:


Click <a href="assets/Mockups/mockups.pdf" target="_blank">Here</a> to view the initial wireframes created for this website.

The above PDF file include wireframes for the following pages for larger screens and mobile devices: 

* Home
* About
* Skills
* Projects
* Contact 

## Features

The page features a navigation bar on the top and a footer on the bottom which both are fixed. 
The naviation bar contains a logotype on the top ledt which is clickable and takes you to the top section of the page (the home page).
It also contains all the different sections on the website (home, about, skills, projects, contact), which takes the user down to the specific section when clicked.
When the screen size is below 768 pixels, the navbar collapses and only showing the logotype and a hamburger button. When the hamburger button is clicked, the diferent sections colapses in a list (which is of course clickable).

The footer is kept as clean as possible and only consists of social media links which will take the user to my social media pages (Twitter, LinkedIn, Github and Slack). 
However, the Slack-logo takes the user to Slacks main page since one need to link the workspace and this is not suitable at the moment. 

#### Home

The home section is the most simpel section on the website. It contains a welcome message, a profile picture and a short scentence of how this website was built (including the icons for each language/library).
The home section is responsive even thoug the profile picture is set to a fixed size. The home section does not change in terms of content between larger and smaller screen sizes.
The home section have a background color which correspond with both the navbar and the footer, thus taking advantage of these element's coverage. 

#### About

The about section have a lighter, gray, background colour to clearly show a section break from the home section. 
The about section mainly consists of a timeline of my previous work/education history. 
Beneth the timeline there is a paragraph and a button for downloading a more exstensive CV. 

#### Skills

The skill section goes back to the blue background to invite the user to the new section. Within the skills section, two different boxes can be found. 
The left box is giving a high level (and subjective) degree of knowledge regarding different languages and technologies. This is presented in form of bars. 
All logotypes of the different technologies/languages are clickable and will take the user the [Wikipedia page](https://www.wikipedia.org/) of the specific language/technology. 
The right section is describing what I believe is good UX. This to give the user a better understanding of my ground pillars in developing apps/websites.


The two boxes are responsive and on smaller screen sizes they are stacked on top of each other.

#### Projects

When we come to the project section, we also comes back to the grey background colour. 
The section is presenting three different projects (two of them fictional at the moment). The projects are presented with a picture and a text. When hovering over the text, the background turns orange. 
However, both the picture and the text act as buttons and when clicking them a modal for the specific project pops up. 
In the modal, the project is breifly presented and the reader have the option to either push a button named "view the code", which will take the user to the GitHub repository or click the button "Close" and leave the modal.

The pictures are responsive and on smaller screen sizes they are stacked on top of each other. 

Below the projects, there is a GitHub icon were the user can click and be linked to all of my GitHub repositories. 

#### Contact

At the end of the page we find a contact form which is covered by a blue background. 
The contact form requires the user to fill in name and email address. Phone number, subject of the question and the text box is optional. 
At the end of the form there is a submit-button, which in the near future will make the form functional (adding JavaScript is required). 

### Existing Features

* Header logotype - When logotype is clicked, the user will come back (up) to the home section.
* Navigation bar - The user is able to easily navigate between the sections by clicking one of the options.
* Footer icons - The footer icons will take the user to my social media pages by clicking on them. 
* About section - contains a button with direct link to my cv. 
* Project section - contains modals for all projects which includes links to view the code. A GitHub icon with link to my all of my repositories is located at the bottom of the section.
* Contact section - contains a contact form for users who want to get in contact with me (no conection at the moment). 

### Features Left to Implement

* Visual effects for the navbar, both in collapsed and non-collapsed mode. In collapsed mode (smaller screen sizes), the navbar should automatically dissapear when a section has been choosen. 
On bigger screens, the navbar should highlight which section the user is currently on. JavaScript is needed to implement these features.
* Email-functionality for contact form. 


## Technologies Used

* The website were build using HTML5 & CSS3.
* The website were developed using [GitPod](https://www.gitpod.io/) as IDE. 
* [Bootstrap4](https://getbootstrap.com/) has been used to easily make the website structured and responsive.
* Icons through out the website been collected from [FontAwesome](https://fontawesome.com/start). 
* The fonts used on the website were collected through [Google Fonts](https://fonts.google.com/). 
* The header logotype were created using [Hatchful](https://hatchful.shopify.com/).
* [W3C's HTLM Validator](https://validator.w3.org/) were used to validate the websites HTML code. 
* [W3C's CSS Validator](https://validator.w3.org/) were used to validate the websites CSS code. 

## Testing 

See [Testing.md](#) for testing done on the website. 

## Deployment

As previously mentioned, the website was build using GitPod as IDE. The code has been pushed to GitHub through the GitPod terminal. 
See on top of this page for the commits made in the IDE to follow the progress of building the website. 
After the code has been pushed to GitHub, a live version of the page were deployed using GitHub Pages. 

## Credits

### Content

* My fellow students at Code Institude gave a second oppinion of the content and design of the website. 
* My sister, Elin Åström, helped me with proof reading the text on the website. 

### Media

* The image on the front page were obtained from [Erik's LinkedIn page](https://www.linkedin.com/in/erik-%C3%A5str%C3%B6m/) and originally captured by [Valcon](https://valcon.com/)
* The images for the Project section were obtained through [Freepik](https://www.freepik.com/) and Shutterstock(https://www.shutterstock.com/home).
* All icons on the website were obtained from FontAwesome(https://fontawesome.com/start)

### Code

* CSS code for the "dots" on the timeline in the About section were taken from Code Institutes "Resumé Mini Project" - but has been modify for this website. 

### Acknowledgements 

* The structure and content of this ReadMe file were inspired by the structure and content of the project [Portrait Artist](https://github.com/AJGreaves/portrait-artist/blob/master/README.md) created by Anna Gilhespy.
* My mentor Brian Macharia provided me with valuable feedback regarding the sites design. 