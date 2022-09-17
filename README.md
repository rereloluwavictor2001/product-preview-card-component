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

- Active State

![image](https://github.com/rereloluwavictor2001/product-preview-card-component/blob/main/design/active-states.jpg)

- Desktop Design

![image](https://github.com/rereloluwavictor2001/product-preview-card-component/blob/main/design/desktop-design.jpg)

- Desktop Preview

![image](https://github.com/rereloluwavictor2001/product-preview-card-component/blob/main/design/desktop-preview.jpg)

- Mobile Design

![image](https://github.com/rereloluwavictor2001/product-preview-card-component/blob/main/design/mobile-design.jpg)


### Links

- Solution URL: [product preview card component repository](https://github.com/rereloluwavictor2001/product-preview-card-component)
- Live Site URL: [product-preview-card-component](https://rereloluwavictor2001.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

I learned how to use gridlayout properly here and also how to position items in a div. I also learnt how to design a responsive webpage.

```html
  <div class="row row-div">
    <div class="image-div col-lg-6">
      <img class="image" src="images/image-product-desktop.jpg" alt="product's image">
    </div>
    <div class="second-container col-lg-6">
      <p id="perf">P E R F U M E</p>
        <h1>Gabrielle Essence Eau De Parfum</h1>
        <p>A floral, solar and voluptuous interpretation composed by Olivier Polge, 
        Perfumer-Creator for the House of CHANEL.</p>
        <div class="row">
          <div class="col-6">
            <h1>$149.99</h1>
          </div>
          <div class="col-6 dollar">
            <span class="dollar">$169.99</span>
          </div>
        </div>
        <p><button type="button" class="btn btn-dark btn-lg"><i class="fa-solid fa-cart-shopping"></i>  Add to Cart</button></p>
    </div>
  </div>
```
```css
@media (max-width: 992px) {
    .row-div {
        width:320px;
        text-align: left;
    }
    .image {
        width: 320px;
        height:480px;
        border-top-left-radius: 8px;
        border-top-right-radius: 8px;
        border-bottom-left-radius: 0;
    }
    .image-div {
        height: 360px;
        
    }
    .second-container {
        padding: 27.646px;
        background-color: white;
        border-bottom-left-radius: 8px;
        border-bottom-right-radius: 8px;
        border-top-right-radius: 0;
        width: 320px;
    }
    .dollar {
        padding:15px 10px;
    }
}
```

### Useful resources

- [MDN docs](https://developer.mozilla.org/en-US/docs/) - This is an amazing article which helped me finally understand div properly and position. I'd recommend it to anyone still learning this concept.


## Author

- Frontend Mentor - [@rereloluwavictor@2001](https://www.frontendmentor.io/profile/rereloluwavictor@2001)
- Twitter - [@rereloluwaalimi](https://www.twitter.com/rereloluwaalimi)


## Acknowledgments

I must really appreciate [Corre Lucas](https://github.com/correlucas). He really helped me with things I needed to work on to improve this little project.

