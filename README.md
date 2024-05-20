# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover and focus states for interactive elements

### Screenshot

#### Desktop view

![](./images/screencapture-127-0-0-1-5500-2024-05-20-15_03_45.png)

#### Mobile view

![](./images/screencapture-127-0-0-1-5500-2024-05-20-15_17_32.png)

### Links

- Solution URL: [solution URL here](https://your-solution-url.com)
- Live Site URL: [live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned how to use srcset to change a picture at certain widths as shown below:

```html
<picture class="product_img">
	<source
		srcset="./images/image-product-mobile.jpg"
		media="(max-width: 600px)"
	/>
	<img
		src="./images/image-product-desktop.jpg"
		alt="picture of perfume on flat surface with leaves"
	/>
</picture>
```

### Continued development

I'd like to time myself in order to finish projects like these much faster.

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - this website is what I used to make sure I used the correct selectors and available properties.
- [ChatGPT](https://chatgpt.com) - I used chatgpt for small queries about my code where I couldn't necessarily see issues.


## Author

- Frontend Mentor - [@Ckola99](https://www.frontendmentor.io/profile/Ckola99)

## Acknowledgments

Here I would like to tip my hat to Kevin Powell and his youtube channel for teaching me new things and ways to use things I already knew in a professional manner.
