# Frontend Mentor - Huddle landing page with alternating feature blocks solution

This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview
Building responsive landing page using HTML and CSS only.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

## My process
- Started by building the desktop first using grid system and then adjusted to smaller devices.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

- How can I position the smaller box on the middle top of the footer section using negative values and z-index for both boxes as well as postioning the smaller box in the middle of the footer using align-self and justify-self.

To see how you can add code snippets, see below:

```css
.middle-box{
    display: grid;
    align-self: center;
    justify-self: center;
    
}
.middle-box .container{
    margin:auto;
    max-width: 500px;
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
    z-index: 1;
    margin-bottom: -80px; 
    background-color: white;   
}
.footer{
    position: relative;
    background-color: var(--Very-Dark-Cyan);
    color: var(--Very-Pale-Cyan);
    padding: 80px;
    width: 100%;
    margin-top: -100;
    z-index: -1;
}
```


### Continued development

Continue focusing on more challages in future projects.


## Author

- Frontend Mentor - [@Zinah-Zwayen](https://www.frontendmentor.io/profile/Zinah-Zwayen)

