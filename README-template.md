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
  - [Useful resources](#useful-resources)

## Overview

### The challenge

- Build a card component and get it looking as close to the given design as possible.
- Users should be able to view the optimal layout depending on their device's screen size.

### Screenshot

![Screenshot](./screenshot.png)

### Links

- Live Site URL: [click here](https://iulso.github.io/stats-preview-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- Sass
- Mobile-first approach
- [BEM methodology](https://en.bem.info/methodology/)

### What I learned

I used the `object-fit` CSS property to adjust the image. This property sets how the content of a replaced element, such as an `<img>` or `<video>`, should be resized to fit its container. You can alter the alignment of the replaced element's content object within the element's box using the object-position property.

```css
img {
  display: block;
  width: 100%;

  @include respond(tab-land) {
    height: 100%;
    object-fit: cover;
  }
}
```

### Useful resources

- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is a comprehensive guide to CSS flexbox layout.
- [object-fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit) - This is a reference for the `object-fit` CSS property.
