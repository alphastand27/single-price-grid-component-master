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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshots/Screenshot%20from%202024-09-08%2018-50-43.png)

### Links

- Live Site URL: [singlepricegridcss](https://singlepricegridcss.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow


### What I learned

Learned some css grid basics for container arrangement and the html tag for line break.

To see how you can add code snippets, see below:

```html
<br>
```
```css
.container {
    display: grid;
    grid-template-rows: 305px 300px 300px;
    justify-content: center;
}
```
```css
.container {
  display: grid;
  grid-template-columns: auto auto;
  grid-template-rows: 245px 300px 300px;
}
```
```css
.service {
  grid-column-start: 1;
  grid-column-end: 3;
}
```

### Useful resources

- [Grid Examples](https://www.w3schools.com/CSS/css_grid.asp) - This helped me learn css grid basics.

## Author

- Frontend Mentor - [@alphastand27](https://www.frontendmentor.io/profile/alphastand27)
- Twitter - [@micheallifexp](https://x.com/micheallifexp)

