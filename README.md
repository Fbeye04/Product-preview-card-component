# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Product component solution](https://github.com/Fbeye04/Product-preview-card-component)
- Live Site URL: [Product live server](https://fbeye04.github.io/Product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Here are the learning points you learned while working on the _Product Preview Card Component_ project:

1.  Tag <picture>:

- What You Learned:
  The `<picture>` tag allows you to display different images based on certain conditions, such as the user's screen size. This is very useful in the implementation of responsive design.
- Usage:
  You use the <picture> element with the <source> tag to replace images based on screen size. On wider screens (min-width: 600px), desktop images are displayed, while for smaller screens, mobile images are used.

``html
<picture>

<source media=“(min-width:600px)” srcset=“./images/image-product-desktop.jpg” />
<img src=“./images/image-product-mobile.jpg” alt=“perfume picture” />
</picture>

````

2. Tag <hgroup>:
- What to Learn:
  The <hgroup> tag is used to group multiple heading elements (<h1> to <h6>) that form a single heading unit. This helps to maintain a good semantic structure of the HTML page.
- Usage:
  You are using the <hgroup> tag to group product category headings (<p id=“perfume”>Perfume</p>) and product names (<h1>Gabrielle Essence Eau De Parfum</h1>).

```html
<hgroup class=“card-text-title”>
  <p id=“perfume”>Perfume</p>
  <h1>Gabrielle Essence Eau De Parfum</h1>
</hgroup>
````

3. Tags:

   - What to Learn:
     The <s> tag is used to indicate text that is no longer relevant or has been removed, such as a price that has been discounted. Teks dalam tag ini akan diberi garis melalui tengahnya.
   - Usage:
     You use the <s> tag to display the price before the discount.

   ```html
   <p class="“card-prices”">
     <span>$149.99</span>
     <s>$169.99</s>
   </p>
   ```

### Useful resources

- [HTML plan to build project](https://fedmentor.dev/posts/html-plan-product-preview/)

## Author

- LinkedIn - [Muhammad Fachrezi Barus](https://www.linkedin.com/in/muhammad-fachrezi-barus/)
- Frontend Mentor - [@Fbeye04](https://www.frontendmentor.io/profile/Fbeye04)
- GitHub - [@Fbeye04](https://github.com/Fbeye04)
