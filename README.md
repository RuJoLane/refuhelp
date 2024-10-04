
URL  https://rujolane.github.io/refuhelp/

URL  https://rujolane.github.io/refuhelp/

POINTS NEEDED in README
* Project overview / features
* 
* UX with user stories
* Manual Testing
* Deployment  X
* Crediting Sources
* Knows bugs
* Future Features


* Project Overview 

The purpose of this site is to provide essential information to refugees new to Chester. In terms of accessibility, design and UX, this meant it must be simple to navigate for those who may speak little English. I did this by - 

* adding a translate tool in the nav bar with a high contrast button and universally recognisable 'translate' icon. Please note that for the purpose of this project the button directs Google Translate. Ideally this button would auto translate the page.

* Selecting a clean, simple font which is available in several languages and similar to printed typeface (Sono), as the landing page features English, Arabic, Farsi and Tigrinya text.

* Selecting high contrast but simple colours for the font and background.

* Using images for context.

FEATURES

* A homepage (index), services directory (directory) and form (volunteer)

* Responsive 'mobile first' design

* nav bar with drop-down menu, translate and logo which directs to home page
<img src="readme-images/nav.jpg.png>

* Footer stuck to bottom of frame featuring social media links

* In-page links which take user back to top on index and directory pages

* Form to submit personal details requiring correct data in fields
<img src="readme-images/form.jpg.png>

* Embedded video in iframe


LIBRARIES USED (see credits for more details)

*I built the responsive layout, nav bar and footer using Bootstrap 4.3.1

*I used Google Fonts to import Sono and Rosarivo via CSS

*I used icons from font awesome.

* UX / Design

The UX is designed to be as simple as possible and easy to navigate. The translate butoon is highlighted in a high contrast colour and contains the universally recognised symbol for translation, in the hope that it draws the ye as the first stop for those who need it.
<img src="readme-images/translator.jpg.png>

Although I approached the design / UX as 'mobile first', I found that I struggled to centre the content for viewing on a small breakpoint. 

I took care to align and balance images, headings and paragraphs, and be consistent with the use of bold font for important information and headings. 

I aimed for simplicity to keep the site as accessible as possible.

I used colorhunt.co to find a base for a blue / teal colour scheme. Research suggested that humanitarian websites often use blue to represent calm, this is apparent on major refugee websites rush as https://www.unhcr.org/ and https://www.refugeecouncil.org.uk/. My aim was for my colour palette to echo sites such as these.

* Testing

  The html showed some small errors in the W3 HTML Validator, but the only one which appeared to affect the functionality of the site was the use of two h1 headings and how they interact with accessibility software such as screen readers. I used an h1 for the site name in the nav and I used h1 for the main strapline which describes what the site is.
  I read up on this using the link suggested by W3 validator, https://html5accessibility.com/stuff/2021/07/08/preserved-in-html/. It seems that all h1s will be treated as headings, I have decided to leave the h1s in as this wokrs well for the site, as a screen reader will read the site name and it's purpose as one heading.

  * I was unable to download and use the Jigsaw CSS validator, but the tutor confirmed in my first attempt feedback that it had already passed.

  * Although I approached the design / UX as 'mobile first', I found that I struggled to centre the content for viewing on a small breakpoint, however the content could still be read. I was uable to find a way in Bootstrap to avoid this., and would like to look into this further in a future version.

After deploying the site I manually tested the following features, all which worked as expected. I had tested as each feature manually as I went, throughout the project.

* Nav Bar
 Expectations -  Logo links to home page, translator links to Google translate Doc page, drop down items all link to relevant sections of relevant pages.

 Actions - clicked on all above links from each page.

 Result - all working as expected.

 * Footer
 Expectation - all social media links open to correct page in new tab

 Action - clicked on each icon from each page

 Result - all working as expected.

 * 'Back to top of page' internal links on index and directory pages

 Expectation - when clicked on, navigates to top of current page

Actions - clicked on all above links from each page.

 Result - all working as expected.

* Form on volunteer page - data fields require correct input, submit button sends data

Actions - inputted both correct and incorrect info in number and email fields to test if they asked for correct data 

Result - I had set the phone number to text, meaning it would accept the wrong data, so I updated the input type to 'number' and re-tested with desired result. All ogher fields working as expected.

* Embedded video on directory page

Expectation - Youtube video will play on clicking play button

Action - when I loaded the page the video was not in the iframe

Result - I used chat GPT to find the error and discovered that a special Youtube embed link must be used. I recitifed this and tested again with the desired result. Originally I had used the video url which was not correct.

* Deployment

I deployed the project using the following steps on GitHub pages

1. Log in and select the Refuhelp repository.
2. From the repository page, clock on setting tab.
3. Scroll to Pages on the left side menu.
4. Select 'main' from Source Menu.
5. Save.
6. The page can then be accessed at https://rujolane.github.io/refuhelp/

I merged both branches before deployment.

* Sources and Credits

Libraries used

Google Fonts
'https://fonts.googleapis.com/css2?family=Sono:wght@200..800&display=swap'
'https://fonts.googleapis.com/css2?family=Rosarivo:ital@0;1&family=Sono:wght@200..800&display=swap'

Bootstrap 4.3.1
https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css

Font Awesome
https://kit.fontawesome.com/7f6bd7f114.js

Features and Media

Google Translate
https://translate.google.co.uk/?sl=auto&tl=en&op=translate

images
chester - https://experiencechester.co.uk/eastgate-clock/

cafe  - istockphoto.com
https://www.istockphoto.com/photo/middle-eastern-people-drinking-coffee-or-tea-in-modern-cafe-gm1818687120-549863858

english - Alamy Stock Photos
https://www.alamy.com/stock-photo/english-concept.html?sortBy=relevant

health - Open Source e-learning LinkdIn
https://www.linkedin.com/pulse/elearning-open-source-nhs-faqs-conor-gilligan/

legal - BDLRP
https://bdlrp.com/free-legal-advice/

Video - Youtube and Share Shop
https://www.youtube.com/watch?v=1P-rnyDzIt0


Troubleshooting

Udemy - Angela Wu's Full Stack Boot Camp
https://www.udemy.com/course/the-complete-web-development-bootcamp

ChatGPT
https://chatgpt.com/

Similar site research 
https://www.unhcr.org/ 
https://www.refugeecouncil.org.uk/


* Future Features

 an auto-translate feature
 a map API showing various services around the city 
 

TROUBLE SHOOTING

I used Angela Wu's full stack dev course videos from Udemy to learn Flexbox and enhance UX knowledge.

I used Chat GPT in a very measured way. I would use it to debug a specific problem if something was not working as expected. I did not ask it write code from scratch for me, although I did ask for a couple of specific examples of how to do things in CSS. I then applied this myself to my code.


