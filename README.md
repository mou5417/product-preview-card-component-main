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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screenshot.jpg)


Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

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

