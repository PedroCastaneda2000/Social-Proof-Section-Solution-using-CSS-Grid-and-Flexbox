# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

In the Social Proof Section, I was tasked to mirror the design of an example page which demonstrates the reviews of the store.

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

*

### Links

- Solution URL: [https://github.com/pgc0004/Social-Proof-Section-Solution-using-CSS-Grid-and-Flexbox.git]
- Live Site URL: [https://social-proof-section-solution-using-css-grid-and-flexbox.netlify.app]

## My process

1. Began with the HTML by laying out the three blocks of content which were the main promotion, main ratings, and main reviews.

2. Then used CSS to specify the position, size, and color of the content inside the blocks.

3. Lastly, the background was positioned in both the desktop and mobile views.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

1. Learned to better manipulate CSS Grid to create two different grids in varying layouts.

2. Learned to use the last-child and nth-child CSS pseudo classes.

```css
.ratings__tab:nth-child(1) {
  grid-row-start: 1;
  grid-column-start: 1;
  grid-column-end: 7;
}

.ratings__tab:nth-child(2) {
  grid-row-start: 2;
  grid-column-start: 2;
  grid-column-end: 8;
}

.ratings__tab:nth-child(3) {
  grid-row-start: 3;
  grid-column-start: 3;
  grid-column-end: 9;
}
```

### Continued development

I will continue to use and manipulate CSS Grid to better implement it into future challenges and continue to use CSS pseudo classes as well.
