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
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./screenshot.jpg)

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
- ARIA landarks
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

- using ARIA landmarks

- vw / vh / vmin / vmax units
- em / rem units
- background images: using multiple images / setting x and y values for positioning

- styling a horizontal rule


```html
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

.card > hr {
    border: 0.02rem solid var(--gray-100);
    width: 100%;
    justify-self: stretch;
}
```

### Continued development

- improve knowledge of background behaviour in responsive design, especially with multiple images.
- next project: focus on using article and section html functions (e.g. a recipe page)

## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/yourusername](https://www.frontendmentor.io/profile/StiTchD-WireD)

