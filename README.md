# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot of the solution](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/webdevbynight/social-links-profile-main](https://github.com/webdevbynight/social-links-profile-main)
- Live Site URL: [https://webdevbynight.github.io/social-links-profile-main/](https://webdevbynight.github.io/social-links-profile-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS (via SCSS)
  - custom properties
  - logical properties
  - grid
- Mobile-first workflow

### What I learned

I learnt the `tech()` function, which can be used together with the `font()` function within the `src` property when writing an `@font-face` rule to declare a variable font:

```css
@font-face {
  font-family: Inter;
  src: ("path/to/Inter.woff2") format(woff2) tech(variations);
}
```

I also learnt that such a declaration replaced the old syntax combining the font format and the font technology.

```css
@font-face {
  font-family: Inter;
  src: ("path/to/Inter.woff2") format("woff2-variations"); /* Old syntax */
}
```

### Useful resources

- [Variable fonts guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_fonts/Variable_fonts_guide) - This helped me to declare a variable font within the `@font-face` rule properly.
- [Description of the `src` property within `@font-face`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/src#description) - This helped me for a proper declaration of the font technology together with the font format.
- [CSS at-rule: `@font-face`: src: `tech(keyword)`](https://caniuse.com/mdn-css_at-rules_font-face_src_tech_keyword) - To check its support by browsers.

## Author

- Website - [Victor Brito](https://victor-brito.dev)
- Frontend Mentor - [@webdevbynight](https://www.frontendmentor.io/profile/webdevbynight)
- Mastodon - [@webdevbynight](https://mastodon.social/webdevbynight)
