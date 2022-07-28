# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./images/Screenshot%20(5).png)
![](./images/Screenshot%20(6).png)

### Links

- Solution URL: [Github Repository](https://github.com/NickTalvy/single-price-grid-component-master)
- Live Site URL: [My Solution](https://nicktalvy.github.io/single-price-grid-component-master/)

## My process

### Built with

- Semantic HTML5 markup
- SASS/SCSS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This was my first project using CSS Grid. I originally thought it would be similar to using Flexbox, but was obviously wrong. After researching grid, it began to make more sense and I like the functionality of it. Though I really struggled in the beginning. I also had to look into shadows and how to format the code. 

a {
        display: block;
        text-align: center;
        color: $lightGray;
        background-color: $brightYellow;
        border-radius: 0.3rem;
        padding: 0.8rem;
        box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);
        transition: background-color 200ms ease;
    }

    @media only screen and (min-width: 62.5rem) {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, auto);

    .join, .cta, .why {
        padding-top: 2.18rem;
        padding-bottom: 2.4rem;
    }

    .join {
        grid-column: 1 / 3;

### Continued development

I definitely need more practice using CS Grid. After this project, im feeling more confident in my knowledge with HTML/CSS, that I think im ready to attempt a project including Javascript. 

## Author

- Website - [My Github](https://github.com/NickTalvy)
- Frontend Mentor - [@NickTalvy](https://www.frontendmentor.io/profile/NickTalvy)