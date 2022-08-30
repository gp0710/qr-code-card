# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Position an element in the center of a screen
without having to play around with margin. Even
with margin, the element will still appear differently on different screens.

```css
div.papa-container {
    position: relative;
}

div.gramp-container {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
```

### Useful resources

- [freeCodeCamp](https://www.freecodecamp.org/news/how-to-center-a-div-with-css-10-different-ways/) - This helped me for centering elements on a screen. I really liked this tutorial and will definitely reference it again in the future.
