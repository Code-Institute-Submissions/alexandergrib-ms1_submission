![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)
# Milestone 1 project

## [Live website on github pages](https://pioneerko.github.io/ms1/)

# Table of contents
- [UX](#ux)
    - [Website owner business goals](#website-owner-business-goals)
    - [User goals](#user-goals)
    - [User stories](#user-stories)
    - [Structure of the website](#structure-of-the-website)
    - [Wireframes](#wireframes)
    - [Surface](#surface)
- [Features](#features)
    - [Existing features](#existing-features)
    - [Features left to implement](#features-left-to-implement)
- [Technologies used](#technologies-used)
- [Code Validation](#code-validation)
- [Testing](#testing)
    - [Funcionality Testing](#functionality-testing)
    - [Compatibility Testing](#compatibility-testing)
    - [User stories testing](#user-stories-testing)
    - [Bugs and problems](#bug-and-problems)
- [Deployment](#deployment)
- [Credits](#credits)


# UX

## Website owner business goals
As the website owner, the goal is to provide information and inspiration and share experience ....

## User goals
- 1
- 2
- 3
- 4
- 5

## User stories
### As a business owner:
- 1
- 2
- 3


### As a new customer:
- 1
- 2
- 3
- 4
- 5

# Structure of the website

The website is optimised for all devices (desktop, mobile and tablet). It is supposed to be user friendly and easy to understand. There are small differences on some pages between mobile and desktop, to have a better visualisation of the content, based on the device. With hover effects and a lot of links (which redirects to websites with more information) the user gets some interaction. By not only having a navigation bar on top of the page, but also having a call to action on every pages body bottom (which leads to the following page), the user has two ways to read through the website.

# Wireframes
Wireframes can be found here: #show images of wirefames


# Surface
## Fonts
Short story about fonts which one is used and which one is for the backup. Why i choose them?

## Colors
To have a harmonic visual impression of the website and to be aligned with the colors shown in the images, I used mainly following colors:
- Body background color: rgba(0, 130, 175, .9)
- Text color: #a7a7a7
- Background color header and footer: #93C47D

## Images
- All images on the website was taken from internet resources with all credit information stated in "Credits" section of this README file.
- Image backup-color: black

# Features
The website is single page, with interactive links to sections on the page with popup window with send me a message form.

## Existing Features
### Navigation Bar (in the Header):
-  Visible on all pages
- Responsive (adapts to burger menu on mobile)
- Left: Logo (linked to homepage) 
- Right 4 Links:
    - Home 
    - Tea traditions(gallery)
    - Tea History
    - Contact me (modulo popup with email and textbar)

### CTA (call to action):
- visible on the bottom of the body in all pages, except of the contact page (last page)
- used as an option to navigate through the website (page by page)

### Footer:
- visible on all pages
- Content: short "about me", link to contact form, social links

### Home (index.html):
- introduction text for what the website is about
- text with general information about New Zealand
- 4 images with links to different pages (in case user is interested in something in particular)

### Route (route.html):
- images of recommended route (screenshot of Google maps)
- explanatory text for screenshot (city by city)

### Accommodation (accommodation.html):
- Text with tips for finding accommodations
- Table with recommended accommodations (includes links to booking websites)

### Highlights (highlights.html):
- List of top 10 highlights to visit with information and links

### Lotr (lotr.html):
- 5 items for lord of the rings fans to visit in New Zealand along the trip
- includes external links for more information

### Gallery (gallery.html):
- image gallery to scroll through

### Contact form (contact.html):
- required form fields: Name, Emailaddress and Message
- On submit, "thank you" alert message will be shown

## Features left to implement:
- embed google maps in the route page: I used a screenshot from Google maps and linked it to a preselected route. Ideally this map would be directly embedded with Google maps. The reason I didn't do it, is that Google changed their requirements of using their Google Maps API.

## Technlogies used:
- HTML: 
- CSS
- Bootstrap
- Fontawesome
- Google Fonts  @import url('https://fonts.googleapis.com/css?family=Roboto:100,200,300,400,500,600,700|Exo:100,200,300,400,500,600,700');
- Github
- Gitpod
- Git
- Balsamiq
- hover.css  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.1.1/css/hover-min.css" type="text/css" />
- 

## Testing
### Functionality testing
### Compatibility testing
### Code Validation
### User stories testing
### Issues found during site development
### Performance testing

## Deployment

## Credits

Skeleton structure of the README.md file was copied from [Jacqueline Kraus](https://github.com/jacqueline-kraus/MS1-Discover-NZ)
Most of my text and educative information was copied from Wikipedia

- [headlines for hero paragraphs](https://theteahouseltd.com/)
- [text shadows example](https://www.codesdope.com/blog/article/adding-outline-to-text-using-css/)
- [Traditions text](https://www.mentalfloss.com/article/72891/15-tea-traditions-around-world#:~:text=Drinking%20tea%20is%20a%20tradition,preparations%20evolving%20along%20the%20way.)
- [Tea history](https://en.wikipedia.org/wiki/History_of_tea_in_China)
- [tea feacts](https://www.healthline.com/nutrition/top-10-evidence-based-health-benefits-of-green-tea#4.-Antioxidants-may-lower-the-risk-of-some-cancers)

### Problems encountered: 
- Git merging branch with local Pycharm. "The “fatal: refusing to merge unrelated histories” Git error"
    - resolved by applying <code>git pull origin master --allow-unrelated-histories</code>
  
  
## Credits for images used:
  - Hero background  Photo by <a href="https://unsplash.com/@procaffeinator?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Arfan Abdulazeez</a> on [Hero img](https://unsplash.com/photos/oi0FvNhkHy8)
  - black tea img Photo by <a href="https://unsplash.com/@og?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Oleg Guijinsky</a> on <a href="/collections/1564860/tea?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a> [black tea](https://unsplash.com/photos/2CRgKZAyPXg)
  - mixed tea Photo by <a href="https://unsplash.com/@stri_khedonia?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Alice Pasqual</a> on <a href="/s/photos/gree-tea?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a> [mixed tea](https://unsplash.com/photos/xdD-x2Y2SPI)
  - mixed 2  Photo by <a href="https://unsplash.com/@stri_khedonia?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Alice Pasqual</a> on <a href="/s/photos/gree-tea?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a> https://unsplash.com/photos/59Kh3TAajg0
  - tea leaves Photo by <a href="https://unsplash.com/@newmanphotog?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Timothy Newman</a> on <a href="/s/photos/gree-tea?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a> https://unsplash.com/photos/_ZH-GRbh0iE
  - green tea Photo by <a href="https://unsplash.com/@teacreative?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tea Creative │ Soo Chung</a> on <a href="/s/photos/green-tea?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a> https://unsplash.com/photos/SpnGFRf0Nmk
  - white tea By <a href="https://en.wikipedia.org/wiki/User:Iateasquirrel" class="extiw" title="en:User:Iateasquirrel">Iateasquirrel</a>, <a href="http://creativecommons.org/licenses/by-sa/3.0/" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=553061">Link</a>
  - puer tea <a href="http://creativecommons.org/licenses/by-sa/3.0/" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=603774">Link</a>
  - teacup Photo by <a href="https://unsplash.com/@teacora?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">TeaCora Rooibos</a> on <a href="/s/photos/tea?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a> https://unsplash.com/photos/FnTWsBohkdo
  - tea tradition 1 Photo by <a href="https://unsplash.com/@lauraadaiphoto?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">laura adai</a> on <a href="/s/photos/tea-traditions?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  - tea tradition 2 Photo by <a href="https://unsplash.com/@igorstarkoff?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Igor Starkov</a> on <a href="/s/photos/teapot?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  - tradition 3 Photo by <a href="https://unsplash.com/@pursuit_of_shutter?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Ranit Chakraborty</a> on <a href="/s/photos/teapot?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  - tradition 4 Photo by <a href="https://unsplash.com/@teacreative?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tea Creative │ Soo Chung</a> on <a href="/s/photos/teapot?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  