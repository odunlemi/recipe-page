# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
<!-- - [Acknowledgments](#acknowledgments) -->

## Overview
### Screenshot

![Mobile version screenshot](./assets/images/mobile_screenshot.png)

![Desktop version screenshot](./assets/images/desktop_screenshot.png)

### Links

- Solution [here](https://github.com/odunlemi/recipe-page)
- Live Site [here](https://odunlemi.github.io/recipe-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I challenged myself to start with a mobile-first design, and then scaled to larger screens. The most important thing was structuring my stylesheet better and targeting the different screen sizes.

Documents my media queries:

```css
/* Mobile views */
@media screen and (max-width: 399px) { }
```
```css
/* For larger screen sizes */
@media screen and (min-width: 400px) and (max-width: 799px), (min-width: 800px) { }
```

### Continued development

- The font-size that fits all content on large screen size, because the last section `nutrition` is currently set to `dispaly: none` on screens from 400px because it overflows.
- Table for the nutritional values

<!-- ### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.** -->

## Author

- Website - [Abiodun Longe](https://odunlemi.github.io/)
- Frontend Mentor - [@odunlemi](https://www.frontendmentor.io/profile/odunlemi)
- Twitter - [@odunlemi](https://www.x.com/odunlemi)

<!-- ## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.** -->
