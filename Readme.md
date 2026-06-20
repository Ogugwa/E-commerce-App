# This is a sample e-commerce site
The aim is to build a prototype and also sharpen my Js skilss
This site will consists of a Landing page with a peoducts displayed
A cart icon that has a counter from items that are added to cart

A cart page that will displayed on click of the Cart icon

A calculator function that calaculates the prices of items added to cart
A little detail of images and description of product added to cart

A checkout page

## Packages
I will be building this site using HTML, Tailwind CSS and Javascript only

## Installation

To install Tailwind Css go to the officail website, we will be using the Play CDN method of installation
[Tailwind Documentation](https://tailwindcss.com/docs/installation/play-cdn)

I followed te instructions on the page
I also had to download Tailwind Intellisense extension from the VsCode Extension market place to help with Auto completion

## Structure
### NavBar
This is the starting point of the web app
This is going to contain the name of the app [DeMarket] host the Home Page, About Us , Contact, Login Page , Sign up Page, Add to Cart Icon, Hamburger menu for mobile
- For mobile the Navbar contains the Add to Cart icon and the Hamburger menu. The menu will host the links to other components of the page not yet available

### Issues
Literally Bugs showed me shege
From the tailwind my margins where not having effects, from m-auto, mx-auto, mt-10, mb-2, i went down the whole rabbit hole with Chatgpt double checking the Devtools and it turns out the issue was from my choice of tailwind.

For this project I was using Tailwin 4 and using CDN installation which accroding to AI sources class
detection can fail depending on how it loads.
So i had to fall back to the classic 
```js
<script src="https://cdn.tailwindcss.com"></script>
```
Rather than the version 4 install. This was a lot cause i spent over 2 hours debugging this.