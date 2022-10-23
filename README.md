# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](images/screenshot.png)

**

### Links

- Live Site URL: (https://faris-thibani.github.io/Single-Price-Grid/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learned to build a website from a mobile first approach. 


It appears that mobile first development makes it alot easier and much more responsive. 

```css
@media (min-width: 1160px){
    .wrapper{
        align-items: center
    }

    .container{
        width: 700px;
        margin: 0 auto;
    }
    .bottom-container{
        display:flex;   
        flex-direction: row;
    }
    .left-bottom{
        width: 350px;
    }
    .right-bottom{
        width: 350px;
    }
    .description{
     width: 90%;
    }
    .story-description{
        width: 65%;
    }
}
```

### Continued development

Perhaps some additional breakpoints. 



## Author

- Frontend Mentor - [@Faris-Thibani](https://www.frontendmentor.io/profile/Faris-Thibani)
