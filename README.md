# Fylo-data-storage-component
Solution for Fylo data storage component Frontend Mentor Junior HTML and CSS Challenge

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

- See hover states for interactive elements.
- View the optimal layout with large screens ONLY.

### Screenshot

![](ScreenShot.png)

### Links

- Live Site URL: [Fylo data storage component](https://abdallahsalah003.github.io/Fylo-data-storage-component/)

## My process

### Built with
ONLY WITH
- Semantic HTML5 markup
- CSS custom properties

### What I learned
I learned after and before Selectors also the linear-gradient.
```
    CSS
    .progress-bar::before {
        content: "";
        position: absolute;
        top: 3px;
        bottom: 3px;
        left: 3px;
        border-radius: 29px;
        height: calc(100% - 5px);
        width: 81.5%;
        background: linear-gradient(to right, hsl(6, 100%, 80%)  ,hsl(335, 100%, 65%));
    }
    .progress-bar::after {
        content: "";
        position: absolute;
        top: 4px;
        bottom: 5px;
        left: calc(81.5% - 10px);
        width: 12px;
        height: 12px;
        background-color: white;
        border-radius: 50%;
    }
```

### Continued development
Why Not!
### Useful resources
- [w3schools](https://www.w3schools.com/howto/howto_css_image_overlay_title.asp)

## Author

- Website - working on it
- [@AbdallahSalah003]
