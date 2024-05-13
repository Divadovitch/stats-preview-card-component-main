# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [My solution](https://www.frontendmentor.io/solutions/stats-preview-card-component-with-flexbox-EH2A26gYmW)
- Live Site URL: [Live preview](https://divadovitch.github.io/stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

That having a space or no space between the pseudo-class `:first-child` does not give the same result

```css
.card__stats__item :first-child{
}
is not the same as
.card__stats__item:first-child{
}
```

### Useful resources

- [Space between classe selector](https://stackoverflow.com/questions/1126338/what-does-a-space-mean-in-a-css-selector-i-e-what-is-the-difference-between-c) - What is the difference between .classA.classB and .classA .classB?.

## Author

- Frontend Mentor - [Divadovitch](https://www.frontendmentor.io/profile/Divadovitch)
