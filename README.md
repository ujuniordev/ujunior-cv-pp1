# Curriculum Vitae website
## Project Portfolio 1

This is a *Curriculum Vitae* website to display to possible recruiters and companies with job openings which I would like to apply to. 
The website contains a short presentation of myself, my coding skills, my CV in a more detailed form and a contact form.

## User experience

The user stories that were used to develop the website are listed below:

 - **US 01 Header**
As a desktop and mobile user, I want to access a menu so that I can navigate easily between the website pages.
 - **US 02 Footer**
As a desktop and mobile user, I want to have access to a footer so that I can easily find the owner's social media links
 - **US 03 Homepage**
As a desktop and mobile user, I want to have access to a homepage with an about section to understand the content of the website 
 - **US 04 Skills page**
As a desktop and mobile user, I want to have access to a skills page detailing the owner's skills so that I can understand the owner's main abilities
 - **US 05 Download page**
As a desktop and mobile user, I want to have access to a download page, with a download button so that I can download the owner's CV
 - **US 06 Contact page**
As a desktop and mobile user, I want to have access to a contact page so that I can contact the owner of the website for more information

### Features

This website contains the following features/pages that were developed considering the user's stories listed in the section User experience above, they should all have responsive behavior allowing navigation on any device:

 - **F01 Header (using US01)**
The header is composed of 2 main elements: the logo and the menu. The logo was developed in pure text and links the user back to the homepage. The menu items are home, skills, cv, and contact. The main goal of the header is to provide easy and quick navigation since the user finds all available pages accessible very quickly.
 - **F02 Footer (using US02)**
The footer is a simple element containing 4 social media icons linking to the social media pages. The main idea is to have a quick way to easily learn more about the owner of the website through his social media.
 - **F03 Homepage (using US3)**
On the landing page of the website, the user will find an about me section, containing a brief summary of the owner's profile with a picture. The goal is to provide all information needed for a complete understanding of the website and push the users to discover more by navigating the other pages.
 - **F04 Skills page (using US4)**
The objective of this page is to list all the relevant skills of the website owner, in order to catch the attention of recruiters. This page is composed of a list of skills icons.
 - **F05 Download page (using US5)**
On the download page, the focus is on the download button, which allows the user to directly download the owner's CV for more detailed information about his profile. The page is simply composed of a call to action and a download button.
 - **F06 Contact page (using US6)**
On the contact page, the user is offered the possibility to send a message to the website owner using the fields: name, last name, company, email, subject, message, and a call to action to send the content via email to the website owner.
By clicking on the SEND button, the customer receives feedback that his message was delivered, which UX-wise is a standard approach in providing the user with information after an action is taken.

### Features to be implemented

 I would like to work on the contact form to make it actually send the message to the destination email, and  also, I would like to create separate files for the header and the footer and using backend programming, simply include those pages where necessary instead of copying the whole header and footer into all the files.

## Design
The following design choices were made: clean and simple fonts & color palettes, consistent with the website's main goal which is to sell the owner's profile as being a serious professional open for new positions.

 - **Wireframes**

	 - W01 Homepage

![Homepage mockup](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/59cc03a74ad1e9d03c9478304fbbfed3ce060048/wireframes/home.png)
![Homepage mockup mobile](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/main/wireframes/home-mobile.png)

	 - W02 Skills page

![Skills mockup](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/main/wireframes/skills.png)
![Skills mockup - mobile](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/main/wireframes/skills-mobile.png)

	 - W03 Download page

![CV Download](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/96dad7bb3d5527ae1cf6b81e188a61dca21af005/wireframes/cv-download.png)
![CV Download mobile](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/main/wireframes/cv-download-mobile.png)

	 - W04 Contact page

![Contact page](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/96dad7bb3d5527ae1cf6b81e188a61dca21af005/wireframes/contact.png)
![Contact page mobile](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/main/wireframes/contact-mobile.png)

## Technologies

 - HTML5
 - CSS3

## Frameworks, font and image libraries, Programs and code websites references used during the implementation

### Frameworks
 - [Git](https://git-scm.com/) was used for version control through [Gitpod](https://gitpod.io/) terminal, using CLI git commands to commit and push to GitHub
 - [GitHub](https://github.com/) is used as the repository for the entire project
### Libraries
 - [Google Fonts](https://fonts.google.com/) was used to add the Montserrat and Hind fonts into the CSS file and was used on all the pages
 - [Font Pair](https://www.fontpair.co/) and [Font Joy](https://fontjoy.com/) were used to find combinations of fonts to be used in the website
 - [Font Awesome](https://fontawesome.com/) was used to add the social network icons and the download CV icon
 - [Flat Icon](https://www.flaticon.com/) was used to add the skills images to the skills page
### Programs
 - [Balsamiq](https://balsamiq.com/) was used to crete the mockups before the implementation of the website, during the planning phase
### Code
 - During the implementation of the website, it made necessary to look for examples and of code and different ways to achieve the required goal. Therefore a couple os community websites were used, such as the [W3C Schools website](https://www.w3schools.com/) was extensively used to check the syntax and code examples, such as forms
 - [Wiki How](https://pt.wikihow.com/) was also used as to find means of make available a file to be downloaded
 - [Developer Mozilla](https://developer.mozilla.org/) was used to help to understand the concept of using display flex orientation on the website
 - [Stack Overflow](https://stackoverflow.com/) was also referenced to find help to understand how to use flex boxes, label images and so on
 - And of course, the [Code Institute LMS](https://learn.codeinstitute.net/) was extensively used especially the Love Running walkthrough project. The footer was done based on the Love Running project´s footer.

## Testing

The testing plan was based on the features described for the website

![Testing plan](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/8c1956848f3c5a24efa6b4a602981ac49718fa12/testing/testing-plan.png)

### Code Validation

 - To check the HTML of the website, I used the [W3C HTML checker](https://validator.w3.org/) 
 - The results are as follows:
	 - Index page
	![Index page html validator result image](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/8c1956848f3c5a24efa6b4a602981ac49718fa12/testing/html-validator-index.png)
     - Skills page
     ![Skills page html validator result image](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/8c1956848f3c5a24efa6b4a602981ac49718fa12/testing/html-validator-skills.png)
     - CV Page 
     ![CV page html validator result image](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/8c1956848f3c5a24efa6b4a602981ac49718fa12/testing/html-validator-cv.png)
     - Contact page
     ![Contact page html validator result image](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/8c1956848f3c5a24efa6b4a602981ac49718fa12/testing/html-validator-contact.png)
     - Feedback page
     ![Feedback page html validator result image](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/8c1956848f3c5a24efa6b4a602981ac49718fa12/testing/html-validator-feedback.png)
- To check the CSS of the website, I used the [W3C CSS3 Jigsaw validator](https://jigsaw.w3.org/css-validator/)
- The result can be seen below:
![CSS3 validator result image](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/8c1956848f3c5a24efa6b4a602981ac49718fa12/testing/css-validator.png)

### Website Responsiveness
To check the website´s responsiveness I carried out a Lighthouse test. The result can be seen below.
Note that the test was made in an Incognito mode browser tab so there were no interferences from extensions from the browser.

![Feedback page html validator result image](https://raw.githubusercontent.com/ujuniordev/ujunior-cv-pp1/8c1956848f3c5a24efa6b4a602981ac49718fa12/testing/lighthouse.png)

## Deployment

The site is hosted within GitHub pages. To deploy it to the repository, the the steps below have to be followed:

- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
- All modifications to the code that have been pushed to the master branch using Git Push will take effect on the live project

A link to the up and running project can be found here - [Ubiraci Costa Junior CV website](https://ujuniordev.github.io/ujunior-cv-pp1/feedback.html)

# How to clone the repository
 - Browse to https://github.com/ujuniordev/ujunior-cv-pp1, which is the repository where the project is located on GitHub
 - Click on the "Code" button´s arrow to open the dropdown menu
 - Select the HTTPs tab and copy the link given there
 - Open “Git Bash” and change the current working directory to the location where you want the cloned directory to be stored
 - Type git clone in the terminal, paste the URL you copied earlier, and press “enter” to create your local clone

 ## Acknowledgements
 A great and heartfull Thank You to my menthor Brian, who took the responsibility to help me during the course of the project in the best possible way. 
 With great advice and insights from his resourceful mind, he helped me to complete this first major task of the entire program.











`python3 -m http.server`
