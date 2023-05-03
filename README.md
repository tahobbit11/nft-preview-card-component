# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/Screenshot%202023-05-02%20220846.png)
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

I learned how to make background images seem transparent

To see how you can add code snippets, see below:

```html
<div class="nft-content">
        <h3><a href="#">Equilibrium #3429</a></h3>
        <p>Our Equilibrium collection promotes balance and calm.</p>
        <ul>
          <li><img src="./images/icon-ethereum.svg" alt="currency">0.041 ETH</li>
          <li><img src="./images/icon-clock.svg" alt="clock">3 days left</li>
        </ul>
      </div>
```
```css
.main-img {
        background-image: url("../images/image-equilibrium.jpg");
        background-position: top center;
        background-repeat: no-repeat;
        background-size: cover;
        border-radius: 20px;
        height: 280px;
     }

     .main-img:hover {
        cursor: pointer;
        opacity: .5;
        
     }

     .nft-image {
        border-radius: 20px;
     }

     .nft-image:hover {
        background-image: url("../images/icon-view.svg");
        background-color: hsla(178, 100%, 50%, .7);
        background-repeat: no-repeat;
        background-position: center;
     }
```

### Continued development

I want to see if in the future I could make this more responsive instead of using static width and height.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

## Author

- Frontend Mentor - [@tahobbit11](https://www.frontendmentor.io/profile/tahobbit11)
