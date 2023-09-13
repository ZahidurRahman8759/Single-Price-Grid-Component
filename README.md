# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./design/final.png)

### Links

- Solution URL: [HTML](https://github.com/ZahidurRahman8759/Single-Price-Grid-Component/blob/700a7c87510315ee05d78b14a06e66a5a5dfcfd0/index.html)
- Solution URL: [CSS](https://github.com/ZahidurRahman8759/Single-Price-Grid-Component/blob/700a7c87510315ee05d78b14a06e66a5a5dfcfd0/style.css)
- Live Site URL: [LIVE SITE](https://zahidurrahman8759.github.io/Single-Price-Grid-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This was my first project with Grid from Front End Mentor. It was fun to work with the grid. I learned how to align items with the grid and also how to add box-shadow in a grid container.

Here is a code of my grid container that includes the alignments and shadow property:

```css
body {
    background-color: hsl(204, 43%, 93%);
    display: grid;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    display: grid;
    grid-template-columns: minmax(auto,350px) minmax(auto,350px);
    grid-template-rows: auto auto;
    box-shadow: 0 10px 8px 0 rgba(0,0,0,0.2);
    border-radius: 10px;
}
```

### Useful resources

- [Stack Overflow](https://stackoverflow.com/) - This site helped me with the box-shadow property. This is a Q&A site where you can question anything about programming.

## Author

- Frontend Mentor - [@ZahidurRahman8759](https://www.frontendmentor.io/profile/ZahidurRahman8759)
