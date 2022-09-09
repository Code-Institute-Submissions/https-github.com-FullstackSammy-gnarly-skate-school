# **Gnarly Skate School**

[Live site](https://fullstacksammy.github.io/gnarly-skate-school/)

The Gnarly Skate School is a private skateboarding school. And the website is a place where you can read about the school and sign up to book a lesson and to have your kids or you learn skateboaring in all its forms. We teach people of all ages and of all skill levels. We offer a safe environment, progress and a lot of fun! 

This website is a one-page website with 4 differents sections. On this website, you as a user will be able to find a beautiful header with navigation, information about the school and pictures. The type of lessons we provide and a sign up form.

![an image of the site in different resolutions](assets/images/ui.jpg)


## **Features**

### **Navigation** 

On the top of the site, you have the navigation bar. The logo or "headline" to the left and navigation options to the right. The following options are:
- Home button (When clicked, takes you to the top of the site)
- About Us button (When clicked, takes you to the About section of the site)
- Lessons button (When clicked, takes you to the Lessons section of the site)
- Sign Up button (When clicked, takes you to the Sign Up section of the site)

![an image of the navigation bar](assets/images/Nav.jpg)


### **Hero text**
On the header, there is a hero text wich zooms in when the site is finished loading. The hero text is clear and tells the user exactly what this site is about.


![an image of the hero text](assets/images/herotext.jpg)


### **Header**

For the header, I chose to have a full background image and put my content ontop of it. The header consists of:
- Navigation bar
- Hero text for the website
- Background image/Hero image

It is very clear to the user what and who the site is for and easy to navigate to different sections.

![an image of the whole header](assets/images/header.jpg)


### **The About Us section**

On the About Us section, you can find all the information you need about the Gnarly Skate School and what they stand for and how you can book a session. There are also 2 pictures to be seen in this section.

![an image of the about section](assets/images/about.jpg)

### **The Lessons section**

Here you can find all the information about the different lessons that are offered. At the time of writing this, there are two lessons available:
- Street lessons (skating on street ramps, down stairs, rails etc)
- Vert lessons (skating on a big ramp)

![an image of the lessons section](assets/images/lessons-section.jpg)

### **The Sign Up section**

This is the part of the website where you as a user can sign up to our roster and we will contact you for booking of lessons. The section consists of:
- A background image 
- A Sign Up form (where you need to fill out all the fields correctly to proceed)

![an image of the Sign Up section](assets/images/signup-section.jpg)

### **Footer**
The footer is at the bottom of the page and shows social media links that will take you to different sites on a new tab. The icons used are from [Fontawesome](https://fontawesome.com):
- Facebook
- Instagram
- Twitter
- Youtube

![an image of the footer](assets/images/footer.jpg)


## **Bugs & Fixes**

I encountered a bug where my background images for the header and the signup page, did not show on the deployed link through Github. I fixed it by changing the directory of the background images. instead of having background-image: `url('/assets/images/hero-image.jpg')` in css I removed the "/" and added "../" for it to work. So it looked like this:
`url('../assets/images/hero-image.jpg')`

I encountered a bug where the second image of the about page dropped out of margin in the Firefox webbrowser (desktop view). I fixed it by re-positioning the images to be centered and by changing the height to 400px.


## **Testing**
### **HTML**
- I tested my html code on [W3C HTML validator](https://validator.w3.org/#validate_by_input) and found no errors.
### **CSS**
- I tested my css code on [W3C css validator](https://jigsaw.w3.org/css-validator/) and found no errors.
### **Accessibility**


- I have confirmed that this site is responsive, by using css grid layout and media queries to size it to different resolutions.
- I have made sure it works on Chrome, Safari and Firefox. I have also tested the website on different physical devised and made sure the site works on them. These are:
  - Iphone 13 pro
  - Samsung Galaxy S21
  - Samsung Galaxy S22

- The form works as it's supposed to. I have borrowed Code Institutes [link](https://formdump.codeinstitute.net/) for forms and you can't sign up unless you fill out all the required fields.

- I made sure that the colors I used are easy to read and go well together. and I tested it on lighthouse in devtools.

![an image of the lighthouse testing](assets/images/lighthouse.jpg)

## **Unfixed Bugs**

There are no unfixed bugs.

## **Deployment**
The site is deployed to GitHub pages and to deploy it you need to do the following:
- Go to your repositories and click on the one you want to deploy
- Click the settings option
- Choose "Pages" in the menu to the left
- Choose "Deploy from a branch" and when choosing branch, choose the branch named "main"
- Lastly, click the "save" button

You can find the live link to my site [here](https://fullstacksammy.github.io/gnarly-skate-school/).

## **Credits**

### **Content**
- The content used for animations of the hero-text was taken from CI [Love Running](https://github.com/Code-Institute-Org/love-running-2.0) project. The desing for the sign up form was also inspired by CI [Love Running](https://github.com/Code-Institute-Org/love-running-2.0) project.

### **Images**
- The free use images used in this project were all taken from [Unsplash](https://unsplash.com/).

