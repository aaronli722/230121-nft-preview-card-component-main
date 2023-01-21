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

![screenshot](https://github.com/aaronli722/230121-nft-preview-card-component-main/blob/main/images/Screenshot.png)

### Links

- Solution URL: [Github](https://github.com/aaronli722/230121-nft-preview-card-component-main)
- Live Site URL: [Github Live Site](https://aaronli722.github.io/230121-nft-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

1. setting height same width of a div box when the width is not fixed number

```css
div {
  padding-top: 100%;
}
```

2. adding an overlay color on an img by positioning

```css
div {
  width: 100%
  height: 100%
  position: absolute;
  top: 0;
}
```

3. center an element in another element without using Flex

```css
div {
  position: absolute;
  top: 50%;
  right: 50%;
  transform: translate(50%, -50%);
}
```

### Continued development

1. Is it a good way to use <main> as the background element? My purpose is to apply CCS flex so as to center the card.

2. Flex gap

Does flex-gap exist? I found the property on the web but nothing happen when I applied it to my code and finally, I have to use margin.

3. how to vertically center svg?

when I added svg (the eth icon and clock icon) to my codes, I found it is at the top-left of the box. I used flex align-items to center them. But is there another way to verically center svg?

4. overlay color on image, is it possible(no need to add a div)?

to apply the hover effect of the main image, I added a div with overlay color. But is there any way that I no need to add a div but just do some css rules to the image?

5. why can't the image fully fill the box?

There is a 1px gap at the bottom and I have to set the height to 99% to fix it.

![](https://github.com/aaronli722/230121-nft-preview-card-component-main/blob/main/images/Screenshot%202023-01-21%20at%2014.03.01.png)

## Author

- Website - [Aaron Li](https://aaronli722.github.io/230118-QR-code-component-challenge-on-Frontend-Mentor/)
- Frontend Mentor - [@aaronli](https://www.frontendmentor.io/profile/luenlun)
- Twitter - [@luenlun](https://twitter.com/luenlun)
