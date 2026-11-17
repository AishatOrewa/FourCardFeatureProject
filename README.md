# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./Images/aitools.png)

### Links

- Live Site URL: [Live Site](https://aishatorewa.github.io/FourCardFeatureProject/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

I'm glad that i got to use class names more flexibly and using media queries.

```html
<article>
  <h1 class="thin">Reliable, efficient delivery</h1>
  <h1 class="bold">Powered by Technology</h1>
  <p class="content">
    Our Artificial Intelligence powered tools use millions of project data
    points to ensure that your project is successful
  </p>
</article>
```

```css
@media screen and (min-width: 375px) {
  * {
    margin: 0;
  }
  article {
    text-align: center;
    width: 50%;
    margin: 0 auto;
  }
  #flex-content {
    display: flex;
    gap: 2rem;
    align-items: center;
    margin-top: 1rem;
  }
  .flex-item {
    background-color: hsl(0, 0%, 100%);
    border-radius: 4px;
    box-shadow: 2px 4px 4px hsl(212, 6%, 44%);
    width: 300px;
    height: 200px;
    font-size: 15px;
    padding: 1rem;
    color: hsl(212, 6%, 44%);
  }
  .double-item {
    display: flex;
    flex-direction: column;
    gap: 2rem;
  }
}
```

## Author

- Frontend Mentor - [@AishatOrewa](https://www.frontendmentor.io/profile/AishatOrewa)
- Twitter - [@AishatOrewa](https://www.twitter.com/AishatOrewa)
