# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Styled Components](https://styled-components.com/) - For styles

### What I learned
Learned about the hover psuedo class and some of its uses.

```css
.cool-hover:hover .hover-view {
    opacity: 1;
}

.cyan-hover:hover{
    color: hsl(178, 100%, 50%);
}
```
Learned more about relative and absolute positioning
```css
.cool-hover{
    position: relative;
}
.hover-view{
    transition: .5s ease;
    opacity: 0;
    background-color: hsl(178, 100%, 50%, 0.4);
    border-radius: 15px;
    padding: 131px;
    position: absolute;
    top: 15px;
    left: 0;
}
```
Learned about the .svg vector image type

```html
<svg width="11" height="18" xmlns="http://www.w3.org/2000/svg"><path d="M11 10.216 5.5 18 0 10.216l5.5 3.263 5.5-3.262ZM5.5 0l5.496 9.169L5.5 12.43 0 9.17 5.5 0Z" fill="#00FFF8"/></svg>
```

### Continued development
-Learn more about available debugging tools
-Practice better positioning

### Useful resources

- [Resource 1](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_image_overlay_opacity) - This helped me in implementing the hover image effect.
- [Resource 2](https://www.youtube.com/watch?v=XEhR_EfKI7o) - I also used this video for the same reason.