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
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

This is the first challenge on the Frontend Mentor website that I am attempting. working through this challege, I hoped do some practice on responsive websites design using css flexbox.

### The challenge

The challenge was to build out this stats preview card component and get it looking as close to the design as possible.
Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot-desktop.jpg)


### Links

- Solution URL: [Solution URl](https://stats-preview-card-component.github.io)
- Live Site URL: [Live Site URL](https://stats-preview-card-component.github.io)

## My process

First I wrote the markup for the project, using the design images as guide.

Next I opened the design images (jpg) in figma. I used Figma throughout the coding process measure spaces and make better judgements about what margins and paddings to use. All pixel measurements were converted to rems to better responsiveness.

Lastly, I wrote the CSS, with media query at the bottom.

### Built with

- HTML5 markup
- CSS
- Flexbox

### What I learned

A major area of concern for me had been how to implement the color overlay on the image without using an empty <div> tag in a <div>. An empty <div> tag in a <div> worked for the overlay, but was a problem once I applied the flex property.

My search for a solution to this problem led me to a similar question on Stack Overflow from where I learned how to apply background color overlays without using an empty <div> tag as overlay over another <div> tag with image background. 

I am particularly proud of this css:

```css
.image-box {
        background: center / contain no-repeat url(images/image-header-mobile.jpg) rgba(170, 92, 219, 0.5);
        background-size: cover;
        background-blend-mode: multiply;
    }
```


### Continued development

For continued development, I will be doing more practice with:
- Flexbox
- Grids
- Backgrounds


### Useful resources

- [Example resource 1](https://www.stackoverflow.com/questions/36679649/how-to-add-a-color-overlay-to-a-background-image) - This helped me for css background color overlay. I really liked this pattern and will use it going forward.


## Author

- Github - [ecoderP](https://www.github.com/ecoderP)
- Frontend Mentor - [@ecoderP](https://www.frontendmentor.io/profile/ecoderP)
- Twitter - [@paulemi](https://www.twitter.com/paulemi)


