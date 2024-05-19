# The Cutting Room

The Cutting Room is a website made for a fictitious barbershop in London. The intended target for the website are men ages 18 to 30.
Men who are looking for haircut.
 
 The main aim of the website is to convert the user to a potential customer by giving them information of the service that they require and then make a booking with a barber. There are various points are the page for them to do so. But one dedicated area of the website which has a booking form.

 ![Responsive Mockup](/assets/img/Responsive%20Viewport%20.png)

## Features

### Existing Features

### Side Navigation

- The website does not have a horizontal navigation bar instead it has a side navigation that is represented by a Hamburger icon.

![Hamburger Icon](/assets/img/Side%20Navigation%20.png)

I have styled it this way
To not take away from the hero image. 

- When the side navigation is not in use the hamburger icon stays on screen in the right hand corner of the screen, so if the user intends to go to a specific section they can either scroll using their mouse or they can click on the icon could pull the menu out which will slide right from the corner of their screen. Clicking any section will make the side navigation slide back in.

The function of this menu works using JavaScript and was taken from W3C Schools.

![Side Menu](/assets/img/Side%20Navigation%20Menu.png)

## Hero Section (HOME)

![hero section](/assets/img/Hero%20Section.png)

- The hero section is the main focal point for a visitor of the website. The main image is a barber shop room with a man sitting in chair. The rest of the website 
Follows a consistent color theme of dark to light colors to keep up with the theme of the hero image. 

- The hero also features two buttons which may be hard to see at first (this has been considered for accessibility however a hover feature as been applied to the buttons in CSS).

![hero section with buttons](/assets/img/Hero%202.png)

#### -Find Your Style
#### -Book Here 

- These are linked to sections of the website in which the user can do the following actions find the service that they are looking for whether this be a hair cut, beard trim, dry shampoo. And Book Here in which the user can book their haircut with one of the three barbers featured on the website.

## About Us  

![About Us](/assets/img/About%20Us.png)

- The about us section is the second option on the side navigation. This area of the website points out the reasons why someone should choose the Cutting Room

- The icon is featured alongside a paragraph of text, this part of the website is mainly information based requiring the user to fo more reading. The rest of the website sections are purely interactive.

## Services

![Services](/assets/img/Services.png)

- The Services section features four images. When a mouse hovers over the image a short description appears over the image with e gradient overlay background this has been done to evoke a positive emotion from the user. The hover has been removed if the website is viewed on smaller devices for accessibility issues

## Our Barbers 

![Our Barbers](/assets/img/Our%20Barbers.png)

- This section of the website features three image cards; three barbers each have a make booking button underneath them which is has a hover effect the button changes color when the cursor is over it.

## Bookings 

![Bookings](/assets/img/Booking%20Form%20.png)

- This section of the website features a booking form with various input fields for a customer to make a potential booking with one of the three barbers. The form starts off stating the opening times of the barber shop and then proceeds for the user to input their details; Name, Email, Date, Time and then the option to select a Barber 

## Footer 

![Footer](/assets/img/Footer.png)

- The footer contains four links to the social media platforms Facebook, Twitter, Youtube and Instagram.

## Testing 

I have tested that the site works well across different browsers. Firefox, Safari, Chrome

It also responds well when viewed on different devices. Some features such as hover effects are disabled on these devices.

## Validator Testing 

### HTML
- No Errors were returned when passing through the official W3C validator.

[Click for Results in html validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fdeana1985.github.io%2F--TheCuttingRoom--%2F)

![html pass](/assets/img/html%20pass.png)

### CSS 
- No errors were returned when passing through the official (Jigsaw) validator.

[Click for Results in CSS validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdeana1985.github.io%2F--TheCuttingRoom--%2F)

![css pass](/assets/img/css%20pass.png)

### Lighthouse Dev Tools

 ## Desktop

- The website scored 93% at Performance on Desktop with 100% in accessibility according to lighthouse Dev Tools

![lighthouse results](/assets/img/Lighthouse%20Desktop%20Performance.png)

## Mobile

- The website scored 78% at Performance on Mobile with 100% in accessibility according to lighthouse Dev Tools

![lighthouse mobile results](/assets/img/Lighthouse%20Mobile%20Performance.png)

## Wave Accessibility (Web accesibility evaluation tool)

[Click for Results in WAVE](https://wave.webaim.org/report#/https://deana1985.github.io/--TheCuttingRoom--/)

# Resolved Issues

## Images

I noticed that when I deployed my website some links to images did not work. I fixed this by naming images correctly and deleting any spaces in filenames.

I decided to place my images within their own folder kept within another folder named assets.

"/assets/img/filename"

## Mainlogo - The Cutting Room

- This was taking up alot of real estate on the hero section of the website, when scaled down to mobile devices was causing issues. I scaled the logo down to a smaller pixel size in a media query which solved problems with other elements of the page being clipped as you can see in the image below the side navigation had been effected as a result of the logo being a certain size. 

![logo issues](/assets/img/Responsive%20Design%20Issues_1.png)

 ## Service Cards

-  Another issue was the Service section when viewing the website on smaller screen widths the service description text would not show which would prove to be useless as users would not be able to read the service information. I added a media query for screens of a maximum width of 430px that removed the CSS hover feature and displayed the text with a gradient overlay over the image to distinguish the text from any obscurring background colours.

![servicedescription](/assets/img/services%20description.png)

## Unfixed Bugs

- There are no outstanding bugs to date.

# Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

  The live link can be found here - https://deana1985.github.io/--TheCuttingRoom--/

  ## Media

- The photos used in the website are from This Open Source site - https://www.pexels.com/ with credit to Pavel Danilyuk

## Content

- The icons in the about us section andfooter were taken from [Font Awesome](https://fontawesome.com/)
- The code for the footer was taken from the CI LoveRunning Project.
