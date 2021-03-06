# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./images/screenshot.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/faq-accordion-card-main-challenge-using-html-and-css-only-jpYoepduw](https://www.frontendmentor.io/solutions/faq-accordion-card-main-challenge-using-html-and-css-only-jpYoepduw)
- Live Site URL: [https://taro2211.github.io/frontendmentor/faq-accordion-card-main/index.html](https://taro2211.github.io/frontendmentor/faq-accordion-card-main/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

- `<details>` tag and its usage in HTML;
```html
<details>
  <summary class="question">
    How many team members can I invite?          
  </summary>
  <p class="answer">You can invite up to 2 additional users on the Free plan. There is no limit on team members for the Premium plan.</p>
</details>
```
- How to use `clamp()` in CSS:
```css
width: clamp(885px, 80%, 1200px)
```

### Useful resources

- [W3schools](https://w3schools.com)
- [Stackoverflow community](https://stackoverflow.com/questions)
- [MDN Web Blog](https://developer.mozilla.org/)

## Author

- Frontend Mentor - [@Taro2211](https://www.frontendmentor.io/profile/Taro2211)
