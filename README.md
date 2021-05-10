# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  <!-- - [Screenshot](#screenshot) -->
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  <!-- - [Useful resources](#useful-resources) -->
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

<!-- ### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.** -->

### Links

- Live Site URL: [GitHub Pages](https://araggohnxd.github.io/stats-preview-card-component/) 
<!-- - Solution URL: [Add solution URL here](https://your-solution-url.com) -->

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


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


### Continued development

This was my first contact with a responsive layout and I had a lot of fun working with it. I look forward to go through deeper learning about this subject.

<!-- ### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.** -->

## Author

- LinkedIn - [Matheus Oliveira](http://www.linkedin.com/in/moliveirac)
- GitHub - [@araggohnxd](https://github.com/araggohnxd)
- Frontend Mentor - [@araggohnxd](https://www.frontendmentor.io/profile/araggohnxd)