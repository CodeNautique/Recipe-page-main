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

## Overview

### Screenshot

![](./Screenshots/Desktop%20Frontend%20Mentor%20Recipe%20page.png)
![](./Screenshots/Tablet%20Frontend%20Mentor%20Recipe%20page.png)
![](./Screenshots/Mobile%20Frontend%20Mentor%20Recipe%20page.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/CodeNautique/Recipe-page-main)
- Live Site URL: [Add live site URL here](recipe-page-main-tau-ebon.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Sass](hhttps://sass-lang.com/) - Syntactically Awesome Style Sheets

### What I learned

I learned how to use Sass preprocessor using BEM (Block, Element, Modifier) and DRY (Don't Repeat Yourself) convention. Moreover, I saw the importance to name classes thoroughly.

```scss
.block {
  &__element {
    &--modifier
  }
}
```
```html
<div class="block"></div>
  <div class="block__element"></div>
    <div class="block__element--modifier"></div>
```
### Continued development

I want to continue focusing on BEM and DRY convention that were again vague for me. I will use more mixin to ease the maintenace of the code.

### Useful resources

- [BEM - resource 1](https://www.alsacreations.com/article/lire/1641-Bonnes-pratiques-en-CSS--BEM-et-OOCSS.html) - This helped me for understanding the BEM convention and the process (in French).
- [BEM - resource 2](https://www.geeksforgeeks.org/understanding-the-css-bem-convention/) - An article which helped me finally understand the importance of using BEM in team project bu also for personal use. I'd recommend it to anyone still learning this concept (in english).

## Author

- Website - [Tomy](https://www.your-site.com)
- Frontend Mentor - [@CodeNautique](https://www.frontendmentor.io/profile/CodeNautique)
- X - [@idev_cloud](https://www.twitter.com/idev_cloud)
