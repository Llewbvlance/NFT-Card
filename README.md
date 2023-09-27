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
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/Screenshot%202023-09-27%20175122.png)
![](./images/Screenshot%202023-09-27%20175205.png)


### Links

- Solution URL: https://github.com/Llewbvlance/NFT-Card
- Live Site URL: https://llewbvlance.github.io/NFT-Card



## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

This was a brilliant project. The main skill that was learnt was how to add a colour overlay onto the main NFT image whilst in hover mode. I have not done this before and learning how to code this will be a great tool going forward for future design. 

Here are the code snippets below for the colour overlay:

```html
<img id="eqimg" src="./images/image-equilibrium.jpg" alt="Image of the NFT art"
       >
       <span class="cyan-overlay">

        <svg class="viewicon" width="48" height="48" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path d="M0 0h48v48H0z"/><path d="M24 9C14 9 5.46 15.22 2 24c3.46 8.78 12 15 22 15 10.01 0 18.54-6.22 22-15-3.46-8.78-11.99-15-22-15Zm0 25c-5.52 0-10-4.48-10-10s4.48-10 10-10 10 4.48 10 10-4.48 10-10 10Zm0-16c-3.31 0-6 2.69-6 6s2.69 6 6 6 6-2.69 6-6-2.69-6-6-6Z" fill="#FFF" fill-rule="nonzero"/></g></svg>
       </span>
```
```css
.cyan-overlay{
    background: hsla(178, 100%, 50%, 40%);

display: none;

height: 400px;

width: 400px;

position: relative;

bottom: 400px;

margin-bottom: -400px;


}

.viewicon{
  margin-left: 180px;
  margin-top: 180px;
}


#NFTIMG:hover span.cyan-overlay{
    display: block;
    cursor: pointer;
}

```

### Continued development

This was a great project and going forward I am definitely looking to explore the pseudo classes and elements more. This is very exciitng for my coding journey. 



### Useful resources

- [Example resource 1](https://wisdmlabs.com/blog/show-color-overlay-image-hover-using-css/#:~:text=The%20CSS%20to%20Apply%20an%20Overlay&text=To%20place%20it%20on%20the,span%20will%20not%20be%20displayed.) - This website was great in assisting me with the colour overlay. 


## Author

- Frontend Mentor - [@Llewbvlance](https://www.frontendmentor.io/profile/llewbvlance)
