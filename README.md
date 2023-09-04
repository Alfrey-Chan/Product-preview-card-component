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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [https://github.com/Alfrey-Chan/Product-preview-card-component]
- Live Site URL: [https://64f65f9c0b26fd2608db25f1--glittering-fairy-9cd8d4.netlify.app/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned the importance of doing CSS resets before you start any project so issues are less likely to occur later on. Additionally, this challenge required me to utlize media queries so the design was responsive.

Some other interesting and notable things that I have learned:

- Swapping images depending on the screen size
  @media screen and (min-width: 750px) {
  #perfume-mobile {
  display: none;
  }

  #perfume-desktop {
  display: block;
  max-width: 50%;
  border-radius: 15px 0 0 15px;
  }
  }

- Setting font:inherit for everything using the universal selector so I can apply any custom font styles to any text

### Continued development

I hope understand the proper usage of width and height so certain elements take up a specified amount of space on all screens. Flexbox is becoming more clear to me, however, I don't fully understand it quite yet. I hope to touch base on grid in the near future.

### Useful resources

- Kevin Powell on YouTube has countless videos that are extremely informative and helpful.
- CSS units, which to use? - (https://www.youtube.com/watch?v=N5wpD9Ov_To)
- CSS em vs rem units - (https://www.youtube.com/watch?v=_-aDOAMmDHI)

## Author

- Website - [Alfrey Chan](https://www.github.com/Alfrey-Chan)
- Frontend Mentor - [@Alfrey-Chan](https://www.frontendmentor.io/profile/Alfrey-Chan)

## Acknowledgments

- Kevin Powell on YouTube
- Web Dev Simplified on YouTube
