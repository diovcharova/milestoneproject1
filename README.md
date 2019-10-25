# Yoga Studio Balance
Milestone Project One: User-Centric Frontend Development - Code Institute

This is a website for yoga studio Balance. The website includes information about the studio, the weekly schedule, the prices and contact information. It also provides a contact form for easier communication.

## Demo 
A demo of the website can  be found [here](https://diovcharova.github.io/milestoneproject1/index.html).

## UX
The website is targeted at potential and current members of yoga studio Balance. For anyone visiting the website, it is important to easily find important sections, such as the contact form, address of the studio. The weekly schedule is of interest for both members and non-members.   
If the user is not a member yet, the alerts and buttons aim to pursuade them to sign up. It is important that the prices page is also clear, as it plays a role in deciding to become a member.  
The design I have chosen is very simple, in order to make the access of information easy and intuitive. The colors, typography and pictures are as neutral as possible, and only complement the main content. 

## Features

### Existing Features
The header and footer in all pages are identical. The navbar expands at a medium size screen, and a button for sign in appears. The footer also consists of sign in and sign up buttons, as well as links to social media and the other pages of the website for easier access. All the sign up and sign in buttons are linked to a modal with a validated form. The weekly schedule is displayed as a neat table at the large screens. At smaller size screens, it displays the columns stacked. The prices page consists of different section for the different possible subscriptions a user that buy. Each section is a card with information on the price and a button to buy it, which is currently disabled. The contact page has the address and contact information, as well as a form, which enables the user to contact the studio more easily. 

### Features left to implement
In the future, I would like to make the schedule more interactive, perhaps by having the user choose a date from a calendar and the classes for that day would load. I would also like to add the functionalities that allow the users to buy a subscription throught the website. Another thing that is left is to implement is the validation that the two passwords, submitted in the sign up form match.

## Technologies Used
1. HTML5
2. CCS3
3. Bootstrap (v4.0.0)
 
## Testing
The access to the different pages of the website is clear and straightforward as both the header and footer provide links to them. The member and non-member user story achieves the intended outcome. The home page provides information about the yoga studio and the practice of yoga, outlining the many benefits. In the schedule page, the users are able to see the classes offered on each day, for each time slot. The relevant teacher is also listed in the table. On the contact page, the address, phone and email are clearly outlined. On a mobile view the picture of the studio disappears to lear up some real estate. The contact form provides the users with the opportunity to easily contact the studio, without leaving the website. The links in the footer to the social media accounts of the studio are also quite useful. They are represented by Font Awesome icons.
All the forms on the website are validated and do not allow submission with invalid input. For example, the email address has to include a '@' sign and if it does not, an error message is displayed, indicating the user is trying to submit an invalid email address. All the fields in the forms are required and the user cannot submit the form with an empty field. 
The social links in the bottom of the page use a 'target="_blank"', so they open in a new tab. It has all been manually tested to make sure it displays what is expected. 
There are no broken links and it has been manually checked they all point to where they are supposed to. 
Different screen sizes have been tested to ensure responsiveness. The website has also been run on various web browsers, such as Chrome, Safari, Internet Explorer and Miscrosoft Edge, leading to the conclusion the website is compatible with all of them. 

## Deployment
The site is hosted on GitHub pages, deployed from the master branch. The site automatically updates whenever there is a new commit on the master branch through the terminal at Cloud9. The landing page is named 'index.html' to ensure the website deploys properly. To run locally, the repository can be cloned into the editor of choice.

## Credits

### Content
All of the content on the website is written by me. 
### Media
The photos used in this site were obtained from various sites for stock images such as [Stocksnap](https://stocksnap.io), [Unsplash](https://unsplash.com), [Pixabay](https://pixabay.com) and [Pexels](https://www.pexels.com). The picture in the callout section in the home page, as well as the pictures in the prices page have an opacity filter applied to make them more neutral to the eye.
### Acknowledgements 
I have received inspiration for the prices page on the site from the site of [yoga studio Balansz](https://balanzs.nl). 
The home page is inspired by the Whiskey Drop website, built in the User Centric Frontend Development module of the course at Code Insitute. 
