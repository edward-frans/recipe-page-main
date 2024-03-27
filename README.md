# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./assets/images/recipe-page-main%20by%20ed.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

i learned the customization of the label hr.


```css
hr {
  border-width: 0.005px;
  border-color: transparent;
  border-bottom-color: #E3DDD7;
}
```

Also about how to show info like a table, but only with divs and some of styles. I think that will be useful in some cases.

```html
<section class="tb-nutrition">
  <div class="row-nt">
    <div class="calories nutrition-key">
      <p>Calories</p>
    </div>
    <div class="calories nutrition-value">
      <p><b>277kcal</b></p>
    </div>
  </div>

  <hr />

  <div class="row-nt">
    <div class="carbs">
      <p>Carbs</p>
    </div>
    <div class="carbs nutrition-value">
      <p><b>0gr</b></p>
    </div>
  </div>

  <hr />

  <div class="row-nt">
    <div class="protein">
      <p>Protein</p>
    </div>
    <div class="protein nutrition-value">
      <p><b>20g</b></p>
    </div>
  </div>

  <hr />

  <div class="row-nt">
    <div class="fat">
      <p>Fat</p>
    </div>
    <div class="fat nutrition-value">
      <p><b>22g</b></p>
    </div>
  </div>
</section>
```

### Continued development

I haven't yet completed the mobile view of the page. I apologize for the delay but I wanted to check on the progress submitted. I assure you that the mobile view will be finished soon.

## Author

- GitHub - [edward-frans](https://github.com/edward-frans)
- Frontend Mentor - [@edward-frans](https://www.frontendmentor.io/profile/edward-frans)
- Twitter - [@@3dward_frans](https://twitter.com/3dward_frans)

