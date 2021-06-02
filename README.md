# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](design/finished-card.png)

### Links

- Solution URL: [https://github.com/CrazedDoggo/FEM-TestimonialsGridSection](https://github.com/CrazedDoggo/FEM-TestimonialsGridSection)
- Live Site URL: [https://crazeddoggo.github.io/FEM-TestimonialsGridSection/](https://crazeddoggo.github.io/FEM-TestimonialsGridSection/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

After experimenting with auto-fit and auto-fill, I found that applying a max-width to the grid seemingly broke it entirely. The grid items would not size down and would "lock" at the min-width instead of wrapping. The grid itself also locked at the max-width instead of scaling down.

My resolution was to simply add a div around the grid to wrap it to add the max-width which resolved the wrapping issue.

However, due to the nature of auto-fit and auto-fill, creating the grid layout given with different spans and heights depending on the width of the device would require media queries. I found that using the current method on the main branch is easier to write and maintain.

### Continued development

Auto-fit and auto-fill are great technologies of grid, however they should be limited to more "uniform" boxes or situations where we are unaware of how many elements we will have. As this layout is pre-defined for different screen-lengths, it did not require it.

### Useful resources

- [Git Branching](https://www.youtube.com/watch?v=QV0kVNvkMxc) - Helped clarify and reinforce knowledge from Git documentation for branching in this project.
- [Grid Wrappers and Maxwidth](https://developer.mozilla.org/en-US/docs/Web/CSS/Layout_cookbook/Grid_wrapper) - Helped clarify and showed a different way to go about max-widths of grids with accessibility.

## Author

- GitHub - [CrazedDoggo](https://github.com/CrazedDoggo)
- Frontend Mentor - [@CrazedDoggo](https://www.frontendmentor.io/profile/CrazedDoggo)