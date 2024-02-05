# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [solution](https://your-solution-url.com)
- Live Site URL: [live site](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- CSS
- Flexbox
- Grid
- Mobile-first workflow

### What I learned

For this challenge, I started from mobile first.

```css
@media(min-width:600px){
  body{
    display: grid;
    place-content: center;
    min-height: 100vh;
  }
  main{
    display: grid;
    grid-template-columns: 1fr 1fr;
    max-width: 600px;
    border-radius: var(--br-size);
    box-shadow: 10px 10px 10px var(--clr-pale-blue);
  }
  .result{
    border-radius: var(--br-size);
  }

}
```

### Useful resources

- [Kevin Powell](https://www.youtube.com/watch?v=KqFAs5d3Yl8&list=WL&index=15)"# results-summary-component" 
