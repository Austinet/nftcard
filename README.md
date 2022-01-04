# nftcard
NFT preview card, a task from Frontend Mentor.

# Frontend Mentor - NFT preview card component solution by Austinet

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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop view](screenshot/desktop-view.jpg)
![Mobile view](screenshot/mobile-view.jpg)
![Active and Hover](screenshot/active-hover.jpg)

### Links

- Solution URL: [Solution ](https://github.com/Austinet/nftcard.git)
- Live Site URL: [Live site](https://Austinet.github.io/nftcard/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

I learnt how to implement linear gradient and an image to the same background.

```html
  <div class="card-image-container">       
    <a href="#" id="view-icon">
      
    </a>    
  </div>
```
```css
.card-image-container:hover {
    background: linear-gradient(hsla(178, 100%, 50%,0.5),hsla(178, 100%, 50%, 0.55)),url("../images/image-equilibrium.jpg");
    background-size: cover;
}
#view-icon {
    display: block;
    width: 100%;
    height: 100%;
}
#view-icon:hover {
  background: url(../images/icon-view.svg);
  background-repeat: no-repeat;
  background-position: center;
}
```

### Continued development
Keep up the good work, keep practicing

### Useful resources

- [Frontend mentor](https://www.frontendmentor.io) 

## Author

- Website - [Udhe Austine Ogaga](https://Austinet.github.io/resume/)
- Frontend Mentor - [@Austinet](https://www.frontendmentor.io/profile/austinet)
- Twitter - [@udheaustine](https://www.twitter.com/udheaustine)



## Acknowledgments

Gratitute to God, Frontend mentor, Google, YouTube, and CTRL + Z.
