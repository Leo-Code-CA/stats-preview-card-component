# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/mysolution-stats-preview-card-component.jpg)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/stats-preview-card-component-challenge-solution-using-flexbox-53Bv4tqxGU)
- Live Site URL: [Live site URL](https://leo-code-ca.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

For this project, I gave myself an additional challenge: building it in four hours maximum! While I’m writing that, I only have half an hour left so… I’ll have to be straight forward.

I used mostly Flexbox to build this project as it’s a tool I really appreciate and know pretty well. It helped me to create the layout without struggling too much. 

```css
.card-text {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: space-between;
}
```

I also used the pseudo-selector `::after`. I have never really built anything using it but for the image purple overlay, I thought it could be a good§ opportunity to do so. It actually worked pretty well!

```css
.card-image::after {
    content: "";
    display: block;
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    background-color: var(--tranparent-violet);
}
```

Except that, I’ve probably been less accurate on the dimensions than usually am because of the time limit. I really focused my energy on being able to finish the project on time and… it seems like it’s done!

### Continued development

I think I should probably have used CSS grid instead of Flexbox because I could have used the `justify-self` property instead of a margin as I did on top of my paragraph. I think it would have been better practice. As I’m still less confident with CSS grid compared to Flexbox, I preferred to play safe and build the project with what I know best because of the deadline I had. However, I’m really looking forward to build some complex layouts with CSS grid, sounds like lots of fun! 

I also would like to improve myself dimensions-wise. Most of the time when I build those “reproduction projects”, I’m never able to find the exact padding or margin they used. It’s pretty close but, still not 100% similar and I definitely would love to submit a “pixel perfect” solution! 

## Author

- Frontend Mentor - [@Leo-Code-CA](https://www.frontendmentor.io/profile/Leo-Code-CA)
- FreeCodeCamp - [@Leo-code](https://www.freecodecamp.org/Leo-code)