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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover state for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Github](github.com/WerSzpe/Product-Preview-Card-Component)
- Live Site URL: [Click here](https://werszpe.github.io/Product-Preview-Card-Component/)

## My process

I started with pure HTML, then imported needed fonts, started stylizing for a mobile view of the website. After that I worked on media query to properly display content for desktop layout with CSS Grid. As there are different pictures for both views I used HTML picture tag to change photo based on the width of screen.

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use picture tag like this

```html
<picture>
  <source
    media="(min-width: 900px)"
    srcset="./images/image-product-desktop.jpg"
  />
  <img src="./images/image-product-mobile.jpg" alt="product image" />
</picture>
```

### Continued development

Notes for the future: how to change image with media query from CSS file.

## Author

- Website - [Weronika](https://github.com/WerSzpe)
- Frontend Mentor - [@WerSzpe](https://www.frontendmentor.io/profile/WerSzpe)
