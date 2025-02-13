# Frontend Mentor - Product Preview Card Component Solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

You can find the screenshots in the design folder:
- Mobile design (320px)
- Desktop design (1440px)

### Links

- Solution URL: https://github.com/himattheww/product-preview-card-component-main
- Live Site URL: https://product-preview-card-component-main-matthew-ionwyns-projects.vercel.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- CSS Flexbox
- Mobile-first workflow
- BEM Methodology
- Montserrat & Fraunces fonts from Google Fonts

### What I learned

During this project, I learned about:

- Using the `<picture>` element for responsive images
- Implementing BEM methodology for better CSS organization
- Creating accessible components with proper ARIA labels and screen reader support
- Working with CSS Grid and Flexbox for responsive layouts
- Managing typography with Google Fonts
- Using CSS custom properties for consistent styling
- Implementing hover and focus states for interactive elements

Some key code snippets:

```html
<picture class="product__img">
  <source media="(min-width: 600px)" srcset="images/image-product-desktop.jpg">
  <img src="images/image-product-mobile.jpg" alt="Gabrielle Essence perfume">
</picture>
```

```css
.visually-hidden:not(:focus):not(:active) {
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  height: 1px;
  overflow: hidden;
  position: absolute;
  white-space: nowrap;
  width: 1px;
}
```

## Author

- Frontend Mentor - [@himattheww]

## Acknowledgments

Thank you to Frontend Mentor for providing this challenge and helping developers improve their coding skills through practical projects.