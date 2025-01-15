# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

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

- See hover and focus states for all interactive elements on the page

### Screenshot

**Web Version**

<img src="./assets/images/Screenshot%202025-01-15%20123304.png" alt="Web Version" width="800">




**Mobile Version**

<img src="./assets/images/Screenshot%202025-01-15%20123904_mobile.png" alt="Web Version" height="400">


### Links

- Live Site URL: [Vercel](https://blog-preview-card-6fnss7gcp-user2830581s-projects.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I learned a little bit about the CSS function clamp() for fluid typography. The code snippet sets a minimum and maximum font size (20px and 24px respectively), and a preferred value to 2vw (2% of the width of the browser window). The browser will try to set the font width to the preferred value based on the viewport width. If the calculated value is smaller than the minimum, the font size will be set to 20px. If the calculated value is bigger than the maximum, the font size will be set to 24px. I tested the preferred value by using Chrome's developer tools.

```css
.text h1{
font-size: clamp(20px, 2vw, 24px);
}
```


### Continued development

I aim to:
- Implement clamp() in future projects to get more comfortable creating fluid designs.
- Learn CSS Grid and learn when to use that over Flexbox.


### Useful resources

- [MDN Wed Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp) & [Smashing Magazine](https://www.smashingmagazine.com/2022/01/modern-fluid-typography-css-clamp/) - Helped me to understand how to use the css clamp() function. 


## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/user2830581)