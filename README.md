# Frontend Mentor - Social Links Profile Solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG92b9m7t).

This is my fourth project from Frontend Mentor! After working on the recipe page, I built this Social Links Profile to practice my Flexbox skills and get comfortable with CSS variables and hover states.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge
The goal was to create a profile card where social links change color on hover. The main focus was on getting the card perfectly centered and making it responsive for mobile users.

### Screenshot
![My Project Preview](./design/design-preview.png)

### Links
- Solution URL: (https://github.com/kiyotaka-codes/social-links-profile)
- Live Site URL: (https://kiyotaka-codes.github.io/social-links-profile/)

## My process

### Built with
- Semantic HTML5
- CSS Custom Properties (Variables for colors)
- Flexbox
- Mobile-first approach

### What I learned
The most interesting part of this project was working with the `:hover` pseudo-class. I wanted the background and text color to switch smoothly, so I used the `transition` property.

Also, centering a card both vertically and horizontally used to be hard, but `display: flex` and `height: 100vh` made it super easy.

```css
/* I spent some time getting this transition right */
a {
    transition: background-color 0.3s ease, color 0.3s ease-in-out;
}

a:hover {
    background-color: var(--Green);
    color: var(--Grey-900);
}
```

## Author
GitHub - @kiyotaka-codes
Frontend Mentor - @kiyotaka-codes