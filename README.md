# Frontend Mentor - Stats preview card component solution

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

### Screenshot 

(./design/desktop-preview.jpg)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM Methodology

### What I learned

I've never used this before, now I understand how it works

```css
.card__img {
      filter: sepia(90%) brightness(60%) hue-rotate(230deg) saturate(600%) contrast(100%) invert(5%) opacity(50%);
}
```

I also learned a different way of centering an element 

```css
.card {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```
and finally I used media queries

```css
@media (min-width: 1440px) {
  ...
}
```

### Continued development

I want to improve my BEM methodology and good HTML semantic skills and I also want to implement CSS preprocessor like SASS.

### Useful resources

- [center div with CSS](https://www.youtube.com/watch?v=mVYgtzDLZfY) - This video helped me to use a new way for centering a div.
- [media queries cheat sheet](https://medium.com/@sawanrathod/css3-media-query-cheat-sheet-1fab77ea3cb8) - This article is really amazing if you are struggling with media queries.

## Author

- Frontend Mentor - [@tamerlantian](https://www.frontendmentor.io/profile/tamerlantian)
- Twitter - [@2301_ian](https://twitter.com/2301_ian)