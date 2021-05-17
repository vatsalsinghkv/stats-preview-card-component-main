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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](/screenshots/Screenshot.png)
![](/screenshots/Screenshot2.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/html-and-css-using-flexbox-and-picture-tag-kr7nBaFLQ)
- Live Site URL: [Add live site URL here](https://vatsalsinghkv.github.io/stats-preview-card-component-main)

## My process

### Built with

- Semantic HTML5 markup
- Picture tag
- CSS custom properties
- Flexbox

### What I learned

I have learned how to work with **picture** tag, **::before** element, **blend-modes**, **variables**, and **rem** units.

```html
<picture>
  <source media="(max-width: 375px)" srcset="images/image-header-mobile.jpg">
  <img src="images/image-header-desktop.jpg" alt="header-image">
</picture>
}
```
```css
picture::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    background: var(--soft-violet);
    mix-blend-mode: multiply;
    width: 100%;
    height: 100%;
}

:root {
    /* Primary */
    --very-dark-blue: hsl(233, 47%, 7%);
    --dark-blue: hsl(244, 38%, 16%);
    --soft-violet: hsl(277, 64%, 61%);

    /* Neutral */
    --white-main-heading: hsl(0, 0%, 100%);
    --white-para: hsla(0, 0%, 100%, 0.75);
    --white-stat-heading: hsla(0, 0%, 100%, 0.6);
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

I will focus on working on projects using javascript or its framework like react. And love to learn frameworks like Bootstrap.

I will work on concepts which I am really not good at but I really find them usefull.
- Canvas
- SVG & Paths
- Animation
- Transition
- Audio & Video Element

### Useful resources

- [Web-Dev resource 1](https://www.w3schools.com) - This helped me in getting know about usefull elements of html in details which I couldn't find in tutorials. Trust me it was really helpfull.

## Author

- Github - [@vatsalsinghkv](https://www.github.com/vatsalsinghkv)
- Frontend Mentor - [@vatsalsinghkv](https://www.frontendmentor.io/profile/vatsalsinghkv)
- Twitter - [@yourusername](https://www.twitter.com/vatsalsinghlv)
- Instagram - [@vatsalsinghkv](https://www.instagram.com/vatsalsinghkv)
