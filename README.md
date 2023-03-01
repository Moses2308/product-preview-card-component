# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screen%20Shot%202023-02-28%20at%205.02.09%20PM.png)

### Links

- Live Site URL: [Add live site URL here](https://spiffy-klepon-aba684.netlify.app/)

## My process

### Built with

- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Media Queries

### What I learned

- I learned how to use the picture element in this project. Previously, I thought the only way to create an image in HTML was with the img element. This project taught me that we can also use the picture element with its additional functionality to choose which image is right for the design based on certain perameters. In this case I used the media attribute to target screen width and select the best size photo based on the width.

```html
<picture>
  <source
    srcset="images/image-product-desktop.jpg"
    media="(min-width: 600px)"
  />
  <img
    src="images/image-product-mobile.jpg"
    alt="Bottle of Gabrielle Essence Eau De Parfum"
  />
</picture>
```

### Continued development

- I also was able to stick to the top down approach to styling elements. As a result, my stylesheet came out more organized and was visually cleaner. It made my styles easier to read and understand. I will to continue to focus on this to improve the quality of my code.
- I would also like to learn more about semantic HTML. As it is, not enough of my html is distinguishable. The divs I use to contain sectoins of the design are not descriptive and make it hard to look through my code and immediately understand what I'm looking at.

### Useful resources

- [Grid Garden](https://cssgridgarden.com/) - This helped me grasp the fundamentals of CSS grid. The simple game reinforces the basics of grid by having you use its properties repeatedly and in different ways to solve the problem.
- [Kevin Powell](https://www.youtube.com/watch?v=B2WL6KkqhLQ&t=3354s) - This video taught me a lot. It introduced me to the method of analyzing and tackling a project. It taught me to start with the most global styles, how to approach making the HTML structure, and about custom properties. Despite watching the video, I attempted the project on my own afterwards and ended with different results. I aspire to get as fluent in design and I hope to soon write styles as comprehensive and logically as him.

## Author

- Frontend Mentor - [@moses2308](https://www.frontendmentor.io/profile/moses2308)
- DEV - [@moses2308](https://dev.to/moses2308)

## Acknowledgments

A big thanks to Kevin Powell. If it werent for his videos and the resources he provides, It wouldve taken me ages to finish this project, and it wouldnt be as good as it is.
