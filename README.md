# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview
i have designed the product preview component as displayed in the front end mentor website

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
I first filled in the HTML part, then i followed the CSS part on the desktop appearance, then i also included media queries for the appearance on a smaller screen 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

one thing that i have learnt is adding media queries to the code so that the website is also responsive on the mobile 

In this challenge we are given two different images, one is for mobile response while the other is for the desktop appearance, this tricky part i tried to solve it, its one of the main challenges that i actually faced while coming up with the challenge 



CSS

.desktop-image{
    opacity:1;
    border-radius: 1rem 0rem 0rem 1rem;

}

.mobile-image{
    opacity:0;
    border-radius: 1rem 1rem 0rem 0rem;
}


@media (max-width:700px){
   .desktop-image {
        opacity: 0;
    }
    .mobile-image {
       opacity: 1;
      
       margin-left: 165px;
       margin-top: 150px;
       
    }

}

What made the difference was the fact that i made the opacity of the desktop image to 1 so that its visible while in desktop mode and i changed the opacity to 0 under media queries so that its not visible


### Continued development

I want to continue get familar with CSS Flexbox

### Useful resources

- [W3 Schools](https://w3schools.com) - This helped me to do HTML and CSS parts 

## Author

- Website - [Raymond Njagala](https://personal-portfolio-web-cyan.vercel.app/)
- Frontend Mentor - [@Rhyz26](https://www.frontendmentor.io/profile/Rhyz26)
- Twitter - [@initial_Rhy](https://www.twitter.com/Initial_Rhy)

