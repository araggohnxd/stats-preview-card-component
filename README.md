# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Desktop](https://github.com/araggohnxd/stats-preview-card-component/blob/master/images/desktop-screenshot.jpg?raw=true)
![Mobile](https://github.com/araggohnxd/stats-preview-card-component/blob/master/images/mobile-screenshot.jpg?raw=true)

### Links

- Live Site URL: [GitHub Pages](https://araggohnxd.github.io/stats-preview-card-component/) 
- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/responsive-card-component-using-flexbox-and-media-queries-_xWOUXXSM)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media Queries

### What I learned

One of the new things I learned doing this challenge was how to monotone an image, using a "filter" container with the color you want to apply and adding the proper `filter` propriety to the image itself.

```css
.main-section .filter {
    background-color: hsl(277, 55%, 51%);
}

.main-section .filter .image {
    -webkit-filter: grayscale(100%);
    filter: grayscale(100%);
    opacity: 0.5;
};
```

I also had my first contact with media queries and it's use to make web pages responsive.

### Continued development

This was my first contact with a responsive layout and I had a lot of fun working with it. I look forward to go through deeper learning about this subject.

### Useful resources

- [A Complete Guide to CSS Media Queries](https://css-tricks.com/a-complete-guide-to-css-media-queries/) - This article helped me to understand media queries and it's uses. Why it exists, how to structure it and when to use it properly.
- [Monotone an Image with CSS](https://css-tricks.com/snippets/css/monotone-image-css/) - This article taught me how to monotone images with only CSS.

## Author

- LinkedIn - [Matheus Oliveira](http://www.linkedin.com/in/moliveirac)
- GitHub - [@araggohnxd](https://github.com/araggohnxd)
- Frontend Mentor - [@araggohnxd](https://www.frontendmentor.io/profile/araggohnxd)
