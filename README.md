# Frontend Mentor - Workit landing page solution

A solution provided by jefflangtech [Workit landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Step by step](#step-by-step)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./preview.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://jefflangtech.github.io/workit/index.html](https://jefflangtech.github.io/workit/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### Step by step

This is the first project where I am really coming back to the basics in order to improve my system of coding overall. 

Here is how it went:
- Set up the design system (1:04)
- Markup the layout (0:50)

Based on my layout sketch I *think* that I'll be creating this page like so:
1. Top nav simple in flex (it doesn't need flex but a more complex nav would)
2. Header-hero section with 3 divs where the SVG components are transformed in position or scale. Thinking I can do this with relative positioning but not entirely sure. The curved border edge I will have to look up how to do
3. Pretty simple grid section for the 1-2-3 parts
4. The "owner headshot" and "Be the first to test" parts actually look fun to implement and I'm thinking that they will be transforms adjusted for media layouts. It looks like each is sized to fit in its own block but is then moved. I'm trying that first
5. Footer again super easy with some centered logos/links

![](./notes-sketch.jpg)

- Readme/notes/plan update (0:20)
- Nav and some media queries (1:02)
  - I was hoping to get the inline padding to shrink in a linear fashion as the screen decreased in size but discovered that the CSS calc function is not that capable...yet
- Header for desktop (2:04)
  - Holy heck getting the curved of that bottom edge, along with the overflow content, was a lot more than I was anticipating. Had to spend a good chunk of time looking up how to implement, using GPT, and finally settled on a clip-path on an absolute position div under the phone image that was then clipped with an ellipse shape

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Website - [JeffLangTech](https://jefflangtech.github.io/)
- Frontend Mentor - [@jefflangtech](https://www.frontendmentor.io/profile/jefflangtech)