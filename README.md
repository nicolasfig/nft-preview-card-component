# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size

### Screenshots

#### Desktop

![](./images/desktop_view.png)

#### Mobile

![](./images/mobile_view.png)

### Links

- Solution URL: [Code](https://github.com/nicolasfig/nft-preview-card-component)
- Live Site URL: [Live site](https://nicolasfig.github.io/nft-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

How to place an overlay over another image and display it on hover, but I had a lot of trouble keeping the view icon opacity full and the background opacity at 0.5

```css
.image .overlay {
  position: absolute;
  bottom: 0;
  opacity: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 300px;
  height: 300px;
  background-color: var(--cyan);
  border-radius: var(--s-8);
}

.image .overlay:hover {
  opacity: 0.5;
}
```

### Useful resources

- [Flexbox Malven](https://flexbox.malven.co/) - Useful flexbox reference as always
- [MDN](https://developer.mozilla.org/en-US/) - MDN the best documentation

## Author

- Frontend Mentor - [@nicolasfig](https://www.frontendmentor.io/profile/nicolasfig)
