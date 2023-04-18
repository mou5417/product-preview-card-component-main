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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![image](./images/Screenshot.jpg)


### Links

- [Solution](https://github.com/mou5417/product-preview-card-component-main)
- [Live Site](https://643d55123edff71badfed92a--inquisitive-douhua-9c287d.netlify.app/)

## My process
- first define main layout with grid
- second adjust elements inside the main-grid
- finally use media query to make resposive change 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

```html
<h1>What I learned</h1>
```
  <picture class="product-img">
        <source srcset="" media="(min-width:600px)">
        <img src="" alt="Gabrielle Essence Eau De Parfum pefume-product-image" />
  </picture>
```css
  .visually-hidden:not(:focus):not(:active) {
      clip: rect(0 0 0 0);  
      clip-path: inset(50%);
      height:1px;
      overflow: hidden;
      position: absolute;
      white-space: nowrap; 
      width: 1px;

    }


  .button:is(:hover,:focus){
      background-color: var(--crl-primary-500green);
  }
```


### Useful resources
- [Css Rest](https://www.joshwcomeau.com/css/custom-css-reset/) - This is an amazing article which has useful info about Css Reset.


- [visually-hidden](https://www.scottohara.me/blog/2017/04/14/inclusively-hidden.html) - This is an amazing article which has useful content about visually-hidden.



## Author

- Website - [YU MOU]
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Kevin Powell

