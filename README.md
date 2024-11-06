# Serenity Relax&Spa

![The website shown on a variety of screen sizes](/documentation/readme/screen-responsive.png)

Serenity Relax&Spa is my fictional spa that I wanted to be my first project because I like to go to a spa and do a massage. The idea started with my interest in the massage & spa so I decided to make a website about it.

This website is for people who are interested in self-care, with chronic pain or muscle tension caused by lifestyle or occupational stress. Serenity Relax&Spa website provides all the informaition for the new and old users who need to know about the spa, spa programs, contact information and a booking form. 

## CONTENTS

* [UX - User Experience](#ux)
  * [Wireframes](#wireframes)
  * [Colours Theme](#colours-theme)
  * [Typography](#typography)
  * [User stories](#user-stories)

* [Features](#features)
  * [Navigation bar](#navigation-bar)
  * [Header](#header)
  * [Home page](#home-page)
  * [The Programs section](#the-programs-section)
  * [The Testimonial section](#the-testimonial-section)
  * [The Footer](#the-footer)
  * [The Spa Programs page](#the-spa-programs-page)
  * [The Booking page](#the-booking-page)
  * [The Success page](#the-success-page)
  * [Features left to implement](#features-left-to-implement)

* [Testing](#testing)
  * [Bugs discovered](#bugs-discovered)

* [Deployment & Local deployment](#deployment-&-Local-deployment)
  * [Deployment](#deployment)
  * [Local Deployment](#local-deployment)

* [Credits](#credits)
  * [Content](#contents)
  * [Media](#media)
  * [Code](#code)
  * [Acknowledgments](#acknowledgments)


## UX

My goal is to make 3 pages, Homepage, Spa programs page and booking form page so I started with sketching roughly out a homepage by hand in a paper and then created in more details in Balsamiq. In the end I created 4 pages, the additional page is the Success page which is essential to have in my website to make it clear to customers when they are booking. I want to make the website look clean and user friendly and have all the essential information.

### Wireframes
[Home](/documentation/wireframe/Home.png)

[Spa Programs](/documentation/wireframe/Spa-programs.png)

[Booking Form](/documentation/wireframe/Booking-form.png)

[Success page](/documentation/wireframe/Success.png)

### Colours Theme
Serenity relax&Spa page is a spa website so the colours I chose are warm and welcome tones which I used [Imagecolorpicker](https://imagecolorpicker.com/) to generate colours from my main image so the colours theme goes great together with my image. Moreover, I used [WebAIM:Contrast Checker](https://webaim.org/) to check the contrast of my colours to ensure they are easy to read for users.

### Typography
I wanted to keep my website simple and clean so I used 2 different font styles. My spa's name and the ending text in the footer, I used [Italiano](https://fonts.google.com/specimen/Italianno?query=ita) because It looks elegant and It is a hand-writing font style which makes it perfect for my page’s name and the rest of the text I used [Lexend](https://fonts.google.com/specimen/Lexend?query=lexen) because It intends to reduce visual stress and improve reading performance for the users. 
Additionally, I use [Font Awesome](https://fontawesome.com/) for my social media icons in the footer to help customers quickly and easily identify my social media sites.

### User stories
1. As a client, I need a simple and easy navigation and a user-friendly design that is a responsive layout for my device so I can find information easily and quickly.
2. As a new client, I want to see images and detailed information about the spa ambience and some of the available programs so that I can decide if It is the right place for me to give it a try.
3. As a new client, I need to find essential information about location, contact details and opening hours clearly and concisely so I can plan my visit or contact the spa.
4. As a client, I want to view all the programs in detail on the website so I can match my needs and decide which program I should do.
5. As a regular client, I want to book the service on the website so that I can reserve my date and time in my schedule.
6. As a massage lover, I want to see if there are special discounts for a member or any promotions, so I can decide if I want to be a member to plan my visit within my budget.
7. As a new client, I want to read testimonials from previous clients so that I can feel more confident about booking a program.

## Features

### Navigation bar  

- The responsive navigation bar including link to the Homepage, Spa programs, Contact and Booking button found on all pages to make it as easy as possible for users.
- The nevigation bar allow the users to go to pages without having to revert to the previous page.

### Header

- The header shows the logo and the navigation. The logo I created in [Canva](https://www.canva.com/en_gb/) which included name and the lotus flower as a background. The symbolic of peacefulness and calm. I use the same colours as in the website to keep it clean and simple.
- The header sticks to the top of all pages and when the users start scrolling down, This will goes with the users to allow accessible at all time to the navigation bar.

![Screenshot of the navigation bar in the website](/documentation/readme/navigation-bar.png)

### Home page

- The home page includes the autoplay carousel to show images of the spa, this section allow users to have a picture of the spa and feel more engage to visit the spa or want to know more about it and the introduction text after the images.

![Screenshot of the home page in the website](/documentation/readme/home-page.png)

### The Programs section

- The programs section allows users to see what programs the website has which shows only 3 programs making the home page not too long and provide the link under the program cards if the users want to see more programs in a new page.
- The program cards show the program's name, description, duration, price and a booking button to nevigate to the booking form if the users want to book the time immediately.

![Screenshot of the programs section in the home page](/documentation/readme/program-section.png)

### The Testimonial section

- This section allows the new users to feel more confident to decide to visit us and hopfully book one of our programs. The customer review section is simple but concise, it shows image of user, feedback and name.

![Screenshot of the testimonials in the homepage](/documentation/readme/testimonials.png)

### The Footer

- The footer section includes the contact us info, address, phone number, email and social media sites for users.
- The social media links are showed in icon and when users click on them, they will open to a new tab which make it easy for the users to keep connected via social media.

![Screenshot of the footer in the website](/documentation/readme/footer.png)

### The Spa Programs page

- This page shows all the programs we have and has the same header and footer as the home page. There are 9 cards used in this page and every cards included an image, program's name, description, duration, price and a booking button to nevigate to the booking form if the users want to book the time immediately.

![Screenshot of the spa programs page in the website](/documentation/readme/programs-page.png)

### The Booking page

- The booking page will allow users to book the program, choose date and time to visit including a message box if they have some special requirement. All the input (except the message box) needs to fill out before submitting the form.

![Screenshot of the booking page in the website](/documentation/readme/booking.png)


### The Success page

- This page will show up to confirm the booking after users have filled in all the required information and summitted the booking form.
- The Success page has the same layout as the booking form to make it simple as possible.

![Screenshot of the success page in the website](/documentation/readme/success.png)


## Features left to implement

Testimonials/Customer Reviews
- I would like to add a textarea where users can write reviews. This section could help sit's owner improve the service and users get to share their experience to another users.

Sign up section
- I would like to add the sign up section after the testimonials in the home page and create a sign up form by using Bootstrap to create form similar to the booking form.


## Testing

Please refer to [TESTING.md](TESTING.md) file for all testing carried out.


### Bugs discovered

- CSS didn't work out for the first deployment
   - When I opened the first deployment in the new tab the website didn't show the style only the plain HTML so I edited the CSS link in HTML and removed the slash(/) to change that to a relative link. Now, all styles show up and work fine.

- The radio button in the Booking form didn't work properly
   - When I click on both radio buttons, they were selected both and can not undo it. I want users select just one button(new or old member)
   - I found out that I have different value for name attribute so to solve this issue, I needed to have a same name to radio buttons. Now It works properly as I wanted.

- During the deployment I have a temporary issue from Github which showed failed to deploy but not something cause by my code.


## Deployment & Local deployment
### Deployment

This site was deployed to GitHub page. The steps to deploy are as folows:
1. In the GitHub repository, go to setting tab.
2. From the source section drop-down menu, select the Master Branch.
3. Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The site is deployed using GitHub Pages - [Serenity Relax&Spa](https://chatlada-nina.github.io/serenity-relax-and-spa/) 

### Local Deployment

#### How to Fork

To fork the repository:
1. Login (or sign up) to Github.
2. Go to repository for this project, [chatlada-nina/serenity-relax-and-spa](https://github.com/Chatlada-Nina/serenity-relax-and-spa)
3. Click the fork button in the top right corner.

#### How to clone

To clone the repository:
1. Login (or sign up) to Github
2. Go to repository for this project, [chatlada-nina/serenity-relax-and-spa](https://github.com/Chatlada-Nina/serenity-relax-and-spa)
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

## Credits

### Content
- The font styles in the Serenity Relax&Spa website were taken from Google Fonts [Italianno and Lexend](https://fonts.google.com/share?selection.family=Italianno|Lexend:wght@100..900)
- The icons in the website were taken from [Font Awesome](https://fontawesome.com/)
- Wireframes I have used is [Balsamiq](https://balsamiq.com/)
- The introduction text and all descriptions including reviews text were modified from [ChatGPT](https://chatgpt.com/)
### Media
- All images were taken from [Pexels](https://pexels.com/)
- Testimonials images were taken from [Wikipedia](https://www.wikipedia.org/)
### Code
- The code to make the booking form and the Footer were taken from the CL[Boardwalk Games](https://github.com/Code-Institute-Solutions/boardwalk-games-v1-sourcecode/tree/main) project and modified to suit the website needs.
- Template code for navigation bar, carousel, cards and customer reviews using Bootstrap classes taken from [Bootstrap v5.3](https://getbootstrap.com/) and modified to suit the website needs.
- The testimonial section was learned and modified from [Specific Youtube Tutorial](https://www.youtube.com/watch?v=MQn-xLjZglc)

### Acknowledgments
I would like to thank you the following people:

* Jubril Akolade - My code Institute mentor.
* Eric - my partner who is always supportive and beleive in me.





