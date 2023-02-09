# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements



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
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

In this fontend project I learn a about BIM which stands for block element modifier and object-oreinted css which have two principles the fist one says separate container from content and the second says separate structure from skin.

Here an example, let say we have 3 buttons that have common padding,font-size and border and they differe in text color. We can write a style for these buttons in the following way.

html

```html
<button class="btn btn--1">Clear </button>
<button class="btn btn--2">Clear </button>
<button class="btn btn--3">Clear </button>
```
css

```css
.btn {
  border: 2px solid limegreen;
  font-size: 1.6rem;
  padding: 1em 2em;
}

.btn--1 {
  color: dodgerblue;
}

.btn--2 {
  color: tomato;
}

.btn--3 {
  color: aqua;
}
```

### Useful resources

- [Andi bell css reset](https://piccalil.li/blog/a-modern-css-reset) - This is an amazing blog which have a css reset that makes your life easier to work with css styling. I'd recommend for anyone who wants to use it.

## Author

- Website - [John]
- Frontend Mentor - [@Gskds](https://www.frontendmentor.io/profile/Gskds)