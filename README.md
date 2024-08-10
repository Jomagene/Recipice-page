Here's the completed and corrected README for your project:

````markdown
# Frontend Mentor - Recipe Page Solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![Screenshot of the recipe page](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Live link](https://jomagene.github.io/Recipe-page/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties (e.g., `@font-face`, CSS variables, utility classes)
- Flexbox
- Mobile-first workflow with media queries

### What I Learned

In this project, I gained a deeper understanding of the following concepts:

- **Font Integration:** Learned how to use `@font-face` with `font-display: swap` for better web performance.
- **Custom List Markers:** Implemented personalized list markers using the `::before` pseudo-element in CSS.

Here's a sample of code I'm proud of:

```html
<figure class="image-container">
  <img
    src="./assets/images/image-omelette.jpeg"
    alt="Simple Omelette"
    class="h-full" />
</figure>
```
````

```css
@font-face {
  font-family: "Outfit";
  src: url("./assets/fonts/outfit/Outfit-VariableFont_wght.ttf") format("truetype");
  font-weight: 400 600;
  font-display: swap;
}

@font-face {
  font-family: "Young Serif";
  src: url("./assets/fonts/young-serif/YoungSerif-Regular.ttf") format("truetype");
  font-weight: 400 600;
  font-display: swap;
}

ul {
  padding-bottom: 25px;
  list-style-type: none;
}

ul li::before {
  content: ". ";
  color: var(--rose-800);
  margin-right: 20px;
  font-weight: 600;
}
```

### Continued Development

In future projects, I plan to:

- Improve accessibility features, such as ARIA roles and more semantic HTML.

### Useful Resources

- [MDN Web Docs](https://developer.mozilla.org/) - A comprehensive resource that helped me better understand `@font-face` and CSS custom properties.
- [CSS-Tricks](https://css-tricks.com/) - This site provided useful tips on how to improve the layout using Flexbox and media queries.

## Author

- Frontend Mentor - [@Jomahene](https://www.frontendmentor.io/profile/Jomagene)
- Twitter - [@Jomagene](https://www.twitter.com/Jomagene)

## Acknowledgments

I would like to thank the Frontend Mentor community for providing feedback and suggestions that helped me refine our skills.
