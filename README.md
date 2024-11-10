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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover state for interactive elements

### Screenshot

![](./result.png)

### Links

- Solution URL: [Solution](https://artemkotko14.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- SASS

### What I learned

This challenge let me try to write my styles using a pre-processor Sass.

I learned how to change the image displayed to suit different image display size using <picture> element:

```html
<picture>
  <source srcset="images/image-product-mobile.jpg" media="(max-width: 700px)" />
  <img src="images/image-product-desktop.jpg" alt="Parfum Image" />
</picture>
```

### Continued development

In my future projects I want to focus on making responsive designs and using Sass extension.

### Useful resources

- [Sass Crash Course](https://www.youtube.com/watch?v=Zz6eOVaaelI&ab_channel=developedbyed) - This video helped me to learn basics of Sass. I really liked it and will use Sass going forward.
- [The Picture element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture#examples) - This is an amazing article which helped me understand the <picture> element.
- [Responsive design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design#precursor_to_responsive_design_mobile_web_design) - This is a great article which helped me understand how to make a design responsive.
- [Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images#why_responsive_images) - This article helped me to learn about the concept of responsive images.

## Author

- Github - [Artem Kotko](https://github.com/artemkotko14)
- Frontend Mentor - [@artemkotko14](https://www.frontendmentor.io/profile/artemkotko14)
