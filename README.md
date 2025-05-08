# Room Homepage

## Welcome ✌🏻

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

Explore the elegant and inviting world of interior design with the Room homepage. Discover affordable plans and captivating designs tailored to your taste.

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

## My Process

### Built With

- HTML5
- CSS3
- JavaScript

You will find all the required assets in the `/design` folder. The assets are already optimized.

There is also a `style-guide.md` file containing the information you'll need, such as color palette and fonts.

### What I Learned

- Implementing interactive sliders for navigation
- Creating an engaging and immersive user experience with captivating design elements
- Enhancing accessibility and usability with hover states for interactive elements

This snippet below one example of stuff I learnt showcasing the transition function, a crucial segment of JavaScript code involved in making this project successful.

```js
function transition() {
    images.forEach((image, indx) => {
        image.style.transform = `translateX(${100 * (indx - currentObj)}%)`;
    });
    descriptions.forEach((desc, indx) => {
        desc.style.transform = `translateX(${100 * (indx - currentObj)}%)`;
    });
}
```

### Continued development

The continuously learning journey of a programmer never ends. This project made me realize that there are many concepts that I need to work upon including fundamentals like flex-box and its properties, to more complex concepts like working with fetch and async await in javascript. These areas are some that I think I need to work more upon in the upcoming future as they highlight some of the most significant regions of web development that are important for every developer to know of. 

These key points mentioned here will help me grow accountable and consistent towards improving at writing good quality code and be a successful full stack developer one day.

## Acknowledgments

I feel like the solutions provided on the website and the continuous doubt solving by industry experts on discord for free is something that is unmatched by anyone else and need to be acknowledged for their efforts in improving me as a developer by suggesting the best practices in your respective tech stack.

**Explore the elegant and inviting world of interior design with the Room homepage.** 🛋️🏡✨
