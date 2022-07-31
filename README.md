# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

My third frontend mentor challenge. This challenge was to build a responsive page showing a product card with some interactive elements.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size (card structure changes if being viewed on a mobile (screen size of 480px))
- See hover and focus states for interactive elements

### Screenshot

![](.images/final-product-screenshot-mobile.png)

I've added a screenshot image to this projects github repository within the images folder.

### Links

- Github repo: (https://github.com/Sochmoot/Product-Preview-Card-Component)
- Live Site URL: (https://sochmoot.github.io/Product-Preview-Card-Component/

## My process

To create this card I used flexbox. I placed 2 containers, 1 for the image and 1 for the perfume details, within a parent flex container which allowed me to position the 2 child containers how I wanted.

To make this card responsive, I used media query to change the structure of the cards if this page was being viewed on a mobile screen (480px)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media query

### What I learned

This was my first time using media query. In order to make this page responsive I used the following code:

@media all and (max-width: 480px) {
  .flex-container {
    display: block;

I changed the display to block so the two child containers would stack on top of each other within the parent container.

Then within the media query I was able to target specific selectors as normal and change their styling to fit the smaller screen, i.e:

.sub-container-1 {
  height: 250px;
  width: 375px;
  border-radius: 10px 10px 0 0;
  overflow: hidden;


### Continued development

I've become much more comfotable with flexbox, but will spend more time understanding media query and attempt to learn CSS Grid for different page layouts.


## Author

- Frontend Mentor - [@Sochmoot(https://www.frontendmentor.io/profile/Sochmoot)
