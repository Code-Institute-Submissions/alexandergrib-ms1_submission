![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)
# Milestone 1 project

## [Live website on github pages](https://alexandergrib.github.io/ms1/)

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
- [Deployment](#deployment)
- [Credits](#credits)


# UX

## Website owner business goals
As the site owner of this imaginary teashop, I want to deliver clean and easy to read information about different types of the tea that exist in the world.  Such as green, black, white and pu’er teas. As a business I want to give opportunity to my visitors personally try different types of tea on weekly subscription basis.  
Also, I wish to help customers to get clear understanding how tea is grown, how it processed and delivered around the globe and end up in their morning cuppa.
## User goals
- Me as a user i want to have easy navigational bar
- Simplicity of reading headlines and have a  clear view of pictures
- Ability to navigate between pages and possibility to return to the home page whiting one click
- Site must be readable under all screen size must include mobile in my case it would be Samsung s8 and it should work with tablet screen and under high res desktop screen
- Web site should contain media gallery inside picture snippets with rounded edges and light border, with a possibility to scroll itself


## User stories
### As a business owner:
- I want to user receive available information about products I have
- Read more information about any specific product displayed by clicking on related image
- Place an order or contact me by filling out “Contact me” form.



### As a new customer:
- 1
- 2
- 3
- 4
- 5

# Structure of the website
The website is setup to be used on as many devices as possible, this includes small mobile phones as well as extra-large 4k tv screens. Website suppose to be easy to navigate between sections by clicking required link in the navbar. Also includes easily accessible contact me form with thank you message after completing and send.
There are small differences on some pages between mobile and desktop, to have a better visualisation of the content, based on the device. 

# Wireframes
Wireframes can be found here: #show images of wirefames


# Surface
## Fonts
I decided to go with google Roboto font and sans-serif as a fall-back font.
I think Roboto font is most used font across whole internet and it would not look too different for the user coming from any website they used to use. 


## Colors
Trying to keep whole webpage in harmonic design and have it associated with “tea” colours, I decided to go for the light green colour for the header and footer and to keep it contrasted but organic in colour I went for the blue-ish for the background. To keep high contrast for the text I set colour to white with black shadow outline.
I used following colours:
- Body background color: rgba(0, 130, 175, .9)
- Text color: #a7a7a7
- Background color header and footer: #93C47D


## Images
- All images on the website was taken from internet resources with all credit information stated in "Credits" section of this README file.

## Text
- While I tried to keep my website filled with some useful information, I have had to copy some text mainly from Wikipedia page. Most text information is credited in “Credits” section in this README file 

# Features
The website is single page, with interactive links to sections on the page with popup window with send me a message form.

## Existing Features
### Navigation Bar (in the Header):
- Visible on all pages and attached to the top of the page
- Mobile view collapse links into “Burger menu” 
- Left side of navbar contains Logo image with active link to homepage
- Right side of navigation bar contain 4 hyperinks:
  - Home
  - Tea traditions(gallery)
  - Tea History
  - Contact me (modulo popup with email and textbar)



### Footer:
- visible on all pages 
- Contain contact up link
- imaginary business address information
- fontawesome icons with links to default home page of linkedin, facebook, githup
- Copyright information


### Home (index.html):
- introduction text for what the website is about
- clickable Pictures with tea icons
- Picture gallery
- History section
- Customers reviews section?
-  About us section


### Contact form (contact.html):
- required form fields: Name, Email address and Message
- On submit, "thank you" alert message will be shown

## Features left to implement:

## Technlogies used:
- HTML: 
- CSS
- Bootstrap
- Fontawesome
- Google Fonts  
- Github
- Git
- Balsamiq

## Testing
- Functionality testing – Google chrome developers tools used to test different screens responsiveness of webpages, as well on actual mobile phone and large scree monitor.
- Code Validation – Lighthouse(google dev tools)
- Issues found during site development – see section problems encountered
- Performance testing Lighthouse(google dev tools)


## Deployment
- Deployment made via GitHub pages.  Fork my repository go to setting on forked repository scroll down to GitHub pages and select active branch to be used.

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
  