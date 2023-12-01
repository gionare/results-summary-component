# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor]

### Screenshot

<img src="design/mobile-design.jpg" width="300")


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

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
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="top-container">
      <h2>Your Result</h2>

      <div class="circle" >
        <p class="result-score"><span>76</span> of 100</p>
      </div>
      <div class="info">
        <b>Great</b>
        <p>You scored higher than 65% of the people who have taken these tests.</p>
      </div>
    </div>
```
```css
/*  pseudo-class in CSS allows you to select elements based on their position within a parent element. */
.buttom-container .row:nth-child(2){
  border-radius: 12px;
  background: var(--red-95-white, linear-gradient(0deg, rgba(255, 255, 255, 0.95) 0%, rgba(255, 255, 255, 0.95) 100%), #F55);
  }
  .buttom-container .row:nth-child(2) b {
    /* Your styles for the <b> element within the second .row */
    color: var(--Red, #F55);
  }
```

### Continued development

i would like to continue focusing on in future projects. These could be concepts of adding action of the actual buttons in the project.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Giorgi Nareklishvili](https://portfolio-giorgi-nareklishvili.vercel.app)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- LinkedIn - [@gionare](https://www.linkedin.com/in/gionare/)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

