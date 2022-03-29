# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for interactive elements

### Screenshot

![](./preview.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Create CSS components then style them:
```html
  <div class="btn_groups flex">
    <button class="btn__green bg-green text-white">
      Download <span class="text-mint">v1.3</span>
    </button>

    <button class="btn__purple bg-purple text-white">
      What is it?
    </button>
  </div>
```

Turn off animation for user prefer it to be off:
```css
@media (prefers-reduced-motion: reduce) {  
    *,
    *::before,
    *::after {
      animation-duration: 0.01ms !important;
      animation-iteration-count: 1 !important;
      transition-duration: 0.01ms !important;
      scroll-behavior: auto !important;
    }
  }
```

### Continued development
_ Add animation for text to appears when user scrolls to content.


### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - Check back on knownledge of using flex-wrap, grid template columns or rows on flex box and grid.
-[Previous-Resource](https://github.com/nottohave/space-travel-website-practice) - old resource for reference when I need help looking back on how to build css custom properties.

## Author

- Website - [Fay D](https://fay-personal-portfolio.netlify.app/)
- Frontend Mentor - [@nottohave](https://www.frontendmentor.io/profile/nottohave)

## Acknowledgments
Thank you for frontendmentor creating this challenge. 
[Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR)