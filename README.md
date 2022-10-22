# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).

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

## Overview

### The challenge

- Build a profile card component as similar to the design shown as possible.

### Screenshot

![Screenshot](./images/screenshot_profile_card_component.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/profile-card-component-using-css-grid-rl4BuTUmOE](https://www.frontendmentor.io/solutions/profile-card-component-using-css-grid-rl4BuTUmOE)
- Live Site URL: [https://monumental-faloodeh-df064f.netlify.app/](https://monumental-faloodeh-df064f.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Acessible HTML5 markup
- CSS custom properties
- CSS grid layout

### What I learned

This challenge was a good way for me to start my learning and applications of CSS Grid Layout. During the process, I also learned more about backgrounds and overlaying elements.

This was the most satisfying code I wrote during the challenge because I was stuck trying to build the background. That's why I'm very proud of the following code:

```css
body {
    /* Background */
    background-color: var(--dark-cyan);
    background-image: url(./images/bg-pattern-top.svg), url(./images/bg-pattern-bottom.svg);
    background-repeat: no-repeat, no-repeat;
    background-size: 60%, 60%;
    background-position: left -30% top -27rem, right -28% bottom -27rem;
}
```

### Continued development

For my next project, I will study and apply the following concepts:

- Flexbox
- Resposive Layout

### Useful resources

- [How to control background images](https://www.youtube.com/watch?v=3T_Jy1CqH9k) - This helped me a lot to build the background.
- [CSS Grid Tutorial](https://youtu.be/RhUuMl3R1PE) - This helped me to understand the main css grid concepts and properties.
- [How to overlap elements in CSS Grid](https://www.youtube.com/watch?v=HFG3BKOqOlE) - This helped me in the part where it was necessary to place an image on top of another between two css grid cells.

## Author

- Frontend Mentor - [@thullyoufrn](https://www.frontendmentor.io/profile/thullyoufrn)
- Linkedin - [Thullyo Damasceno](https://www.linkedin.com/in/thullyo-damasceno-375083231)
