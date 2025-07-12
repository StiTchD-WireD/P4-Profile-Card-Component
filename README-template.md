# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Build out the project to the designs provided

### Screenshot

Mobile:  

![./images/Screenshot Profile card component Mobile.png](./images/Screenshot%20Profile%20card%20component%20Mobile.png)


Browser:

![./images/Screenshot Profile card component Browser.png](./images/Screenshot%20Profile%20card%20component%20Browser.png)


### Links

- Solution URL: [GitHub](https://github.com/StiTchD-WireD/P4-Profile-Card-Component)
- Live Site URL: [GitHub Pages](https://stitchd-wired.github.io/P4-Profile-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- ARIA
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

- Introduction to the use of ARIA landmarks.

- Background: using multiple images / positioning of images over the boundries of the pages

- Units: vw / vh / vmax / vmin / rem / em

- Horizontal Rule styling


```html
<div class="card" role="main">
<section class="header" role="banner">
<section class="stats" role="region">
<footer class="footer" role="contentinfo">
```
```css
 background-position: -10vw -50vh, 55vw 65vh;
    background-size: 70vw 75vh, 100vw 75vh;

 border-radius: .65rem;
    margin:  20vh auto;
    max-width: 20rem;

box-shadow: 0 1.5rem 4rem rgba(0, 0, 0, 0.15);

.card > hr {
    border: 0.02rem solid var(--gray-100);
    width: 100%;
    justify-self: stretch;
}

```

### Continued development

- Future: learn more about background and images (all functions and attributes)

- Next Project: focus on html articles and sections, and css grid.


## Author


- Frontend Mentor - [@StiTchD-WireD](https://www.frontendmentor.io/profile/StiTchD-WireD)

