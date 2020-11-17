# Milestone Project 1 [Wellness Centre](Rowy2105/MS1-Wellness-Centre)

To present knowledge and understanding of modules learned by developing and implementing a static front-end web application using
languages HTML5 and CSS3. 

---

![Lotus Logo](assets/images/lotuslogo.png)
## Central Wellness: The Wellbeing Hub.

---

[Rowy2105/MS1-Wellness-Centre](Rowy2105/MS1-Wellness-Centre) Live Website.\
[Github Repository](https://github.com/Rowy2105/MS1-Wellness-Centre).

### **Table of contents**
 * Overview
 * User Stories
 * User Experience. (UX)
 * Features
 * Technologies Used
 * Testing
 * Barriers & Solutions
 * Deployment
 * Resources
 * Credits
 * Acknowledgements

---

### **Overview**

A wellness centre aims to promote positive mental and physical wellbeing to the community, under one roof, by not only providing a gym with fitness 
classes but also by having experienced practitioners on site to help with other needs such as physiotherapy and acupuncture.

---

### **User Stories**

**_“As a visitor of the centres website I....”_**

“need the contact information to be at hand for when I need to get in touch.”\
“want to feel and be a part of the centres community via social media platforms.”\
"want to visit the site and be able to book classes/therapies using my mobile phone for when I'm on the go.”\
“need to know opening times and class timetables so I can work it into my busy lifestyle.”\
"I want to be able to navigate through the site easily getting and efficiently."\
"I want to hear other peoples thoughts on the place."

---

### **User Experience. (UX)**

---

### **The Strategy Plane**

<ins>Main goal of the site is to attract and retain a solid member base.</ins>

**How can this be achieved?**

**_Target Audience_** - People who are isolated, people who are keen to get and keep fit / heal, lose weight, maintain overall wellbeing and generally look after oneself.
* Class timetable with prices.
* Available therapies.
* Contact page – contact form for any queries such as therapy booking and pricing and cancellations etc. 
The centres address and phone number will be provided on the contact page.

**_Creating an online community:_**
* Links to social media platforms: Raising awareness of current health issues and how these can be overcome - selfcare and supportive environment. In reality the links would link to the centres social media site.
* “What are you looking for?” Picture gallery – Reassuring Images: Smiling people at the gym and in classes, therapy rooms.
* Mobile- first approach to site design.

**_Short, informative and concise text._**
Introduction and Welcome Text. About Text including optional therapies and testimonials. 

### **The Scope Plane**

**_Features and Functions_**
* Fully responsive mobile first website – accessible to view from mobile devices, tablets and computers.
* Mobile device drop down nav bar.  Other devices nav bar text in the header section.
* Contact form – Drop down list on what the query is regarding, placeholder text, user query text box and submit button.
* “What are you looking for?” Picture gallery. Each picture will tie in with a reason for visiting the site.

Bootstrap is utilised to create the above and all features are kept within own abilities at this stage of the course.

### **The Structure Plane**

* Nav bar is located in the header section of each page.
* There are four separate pages on the site: Home, About, Classes and Contact.
* Social media links are located in the footer section of each page.
* All text will be short and concise and images will be used to keep an even visual balance to the user to maintain engagement with the site.
* The contact form will be presented on its own page as to not visually confuse the user.  It will have a drop box format for the user to choose what their reason is for contacting the centre with a message box for them to elaborate their reason in.
* The contact page will also contain the centre's address and phone number located below the contact form.

### **The Skeleton Plane**

<img src="assets/wireframes/Wireframes-pdf-1home.png" >
<img src="assets/wireframes/Wireframes-pdf-2about.png" >
<img src="assets/wireframes/Wireframes-pdf-3classes.png" >
<img src="assets/wireframes/Wireframes-pdf-4contact.png" >

The site has four pages; Home, About, Classes and Contact.\
Each page has a navigation bar and footer.  The navigation bar links a page heading to the page.\
The footer bar contains © and social media links.
The about page on the mobile browser will not contain pictures next to the testimonials.

### **The Surface Plane**

* **_Colour Scheme_**

The original colours chosen were pastels constisting of two shades of orange (#FFA351FF, #FFBE7BFF) and a yellow (#EED971FF) with the intention of providing a calming and fresh feel to the website.\
However the colour scheme did change in the coding process as it was apparent that the three colours continously displayed together were visually too much.  This was overcome by sticking with a pastel orange rgb(255, 167, 85) and using a light grey rgb(231, 229, 229). The grey and the orange contrast each other nicely also allowing the text to be more readable.  

* **_Font_**

The font used for all of the text was "Rubik" as it is clear to read and soft on the page due to it's rounded edges.  The line and word spacing used also contributed to the clarity of the text.
The Headings for each page have a the light grey colour for their background and each heading wording is placded with in a span adding to the design effect on each page.
All of the pages text has a colour of rgba(0, 0, 0, 0.5) as the 0.5 transparency makes the black appear less harsh.

* **_Imagery_**

The images chosen were to reflect the text displayed above on the homepage as a reason to why a user wouldn want to visit the site and continue to the other pages. The thought of people relaxing, smiling and exercising was behind the proccess of pick them.

---

### **Features**

The header/navbar and footer will be featured across all pages. They will not be fixed.\
The pages will scroll on all devices.\
A moving image gallery (carousel) welcoming the user to the site.\
The company logo is displayed in the corner of every page and when pressed will redirect the user back to the homepage.\
On larger browsers the nav bar will be displayed on the screen.  On mobile devices and smaller tablets it will be shown as a menu icon that has a toggle function.\
An interactive class timetable. When a row is clicked it has a darker background making it easier to read. Especially useful for mobile devices as the table has to be scrolled horizintally to view all the days.

* **_Features to be implemented with more advance skill base._**

Working Send button.\
A booking system for classes.\
Modal pop up for COVID alert and procedures.

**Due to time being a factor it would have been good to add a download link of the timetable so users could keep a copy of it on their device for convenience.**

---

### **Technologies Used**

* HTML5 
* CSS3
* Bootstrap
* Fontawsome
* Google Fonts 
* Gitpod 
* Github 
* Git 

---

### **Testing**

Testing the responsiveness for all browsers was carried out throughout the development process using Devtools and also casting and inspecting on my own devices to hand.

#### **_Testing against user stories_**

**_“I need the contact information to be at hand for when I need to get in touch.”_**\
The phone link on the contact page works on all browsers.  The contact form and address details is also available.

**_“I want to feel and be a part of the centres community via social media platforms.”_**\
All social link icon in the footer were tested to confirm they redirect to the appropriate social media sites in a seperate browser tab.

**_"I want to visit the site and be able to book classes/therapies using my mobile phone for when I'm on the go._**\
The contact form is available on mobile devices and the phone number link.

**_“I need to know opening times and class timetables so I can work it into my busy lifestyle.”_**\
Responsive class timetables are working on all browsers.

**_"I want to be able to navigate through the site easily getting and efficiently."_**\
The logo was tested to confirm it links to the homepage, index.html.\
All the navbar list items on all browsers were tested on all of the pages to confirm they link to the correct pages.  The navbar menu button was tested also to confirm it works on mobile and tablet devices.

#### **_Barriers and Solutions._**

The footer displayed in the middle of the pages where there was not enough content to keep it pushed down.  This was solved by using flex ["that does not assume fixed heights or changing position of elements"](https://stackoverflow.com/a/45762747).

During testing the responsiveness on the contact page, the transition from the desktop to a tablet was making the contact form display wide across the whole screen.  The random stretch of the form displayed terribly. The problem was solved by adding a media query to the CSS for medium sized browsers with margin declaration.

On the desktop browser all the images on the site were taking very long to download or were not showing at all on the page just the 'alt' message of the picture.  CI mentor sent the link to the [image compressor](https://compressjpeg.com/) and explained that the pictures were too large resulting in the long loading time.  After compressing the images they download fine now when testing on all browsers.

On the first test of my HTML code through the [W3C Markup Validator](https://validator.w3.org/) only one error was shown on all of the pages.  The error was on the contact page within the <form> element.  It would not accept 'label for="name"' as an id of name was not below within the input element. id="name" was added and the error was corrected.

All HTML code was run through the [W3C Markup Validator](https://validator.w3.org/) and all CSS code was run through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input).On my final test of all the code no errors were shown.\
The error for CSS was 'float:center;' which is invalid and therefore removed without any disruption to the site.

All CSS code was put though [Autoprefixer](https://autoprefixer.github.io/) adding -webkit- and -ms- throughout.

---

### **Deployment** 


#### **_Deployment to git hub pages._**


The project was devloped using Gitpod, an Integrated Development Environment (IDE).

In Gitpod using the terminal screen, work was committed to git that keeps track of any changes and then pushed to GitHub.

The process of deploying the page from the GitHub respoasitory to GitHub pages was as follows:

Logged into GitHub and selected the repository: [Rowy2105/MS1-Wellness-Centre](Rowy2105/MS1-Wellness-Centre).

The settings icon was selected.

Scrolled down the settings page to GitHub pages section.

Master branch was selected on the dropdown menu under source.

The page refreshed and then deployed.

The live link of the website is then found in GitHub pages part of settings.  "Your site is published at ["https://rowy2105.github.io/MS1-Wellness-Centre/"](https://rowy2105.github.io/MS1-Wellness-Centre/).

#### **_Clone, Install and Run Code_**

On the mainpage of the GitHub repository click the green "Code" button.

On the clone tab click on the clipboard icon and that copies the URL.

The URL can then be pasted into an external IDE's directory to create a clone.

Alternatively select "open with GitHub Desktop" and this will clone using GitHub.

---

### **Resources**

All further reading taken place to consolidate and improve knowledge and understanding was taken from:\
[W3schools](https://www.w3schools.com/)\
[MDN webdocs Mozilla](https://developer.mozilla.org/)\
and [Code Institute's](https://courses.codeinstitute.net) module content; All key fundamental elements which underpin the developing process as a whole.\
[Youtube](https://youtube.com) was also used as a learning aid.

[W3C Markup Validator](https://validator.w3.org/) used to check all html code for syntax errors.\
[W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) used to check all CSS code for any errors in the code.\
[Autoprefixer](https://autoprefixer.github.io/) used to check all css code producing -webkit- and -ms-.\
[Balsamiq](https://balsamiq.com/) was used to create the wireframes\
[Atlassian](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet) Basic Git Commands Cheat Sheet.\
Github [markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) was used a point of reference when using Markdown language.\
[PDF to PNG](https://pdf2png.com/) Conversion.\
Anna Greaves [README Video](https://www.youtube.com/watch?v=7BteidgLAyM&feature=youtu.be).\
[Image Compressor](https://compressjpeg.com/). Image optimiser to compress images to their most minimal size.
The original colours the design was based on were choson from [Design Wizard](https://www.designwizard.com/blog/design-trends/colour-combination).

---

### **Credits** 

The lotus flower logo image was taken from [clipart-library](http://clipart-library.com/clipart/500336.htm) a free picture art gallery.\
Code Institute's gitpod template designed with the extentions that are needed for the project.\
Code to prevent the footer from being displayed in the middle of page was sourced as an answer from the stackoverflow forum: https://stackoverflow.com/a/45762747
Code for changing the color of the bullet points was taken from [W3schools](https://www.w3schools.com/howto/howto_css_bullet_color.asp) and [geeks for geeks](https://www.geeksforgeeks.org).\
 Carousel snippet taken from [Bootstrap](https://getbootstrap.com/docs/4.0/components/carousel).\
Navbar snippet taken from [Bootstrap](https://getbootstrap.com/docs/4.1/components/navbar/).\
Form snippet taken from [Bootstrap](https://getbootstrap.com/docs/4.0/components/forms/).\
All photos have been sourced [Pexels](https://www.pexels.com/) a free stock photo source.\
Box shadow codes edited from [colorlib](https://forums.colorlib.com/t/how-to-add-shadow-on-the-menu-bar-and-footer/15062/4) forum.\
Linear gradients code edited from [Mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient()).\
Drop shadow codes edited from [Mozzila](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/drop-shadow()).


---

### **Acknowledgements** 

Anna Greaves [README Video](https://www.youtube.com/watch?v=7BteidgLAyM&feature=youtu.be).

Jim Lynx - User Centric Frontend Development Lead. Zoom lessons for MS1 planning and workflow with Git, Gitpod and Github.

Malia Havlicek for the Zoom lesson on Debugging CSS with Devtools.

The Slack Community for asking and answering all the right questions. A fantastic support network. 
