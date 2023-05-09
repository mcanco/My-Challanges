# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)
![desktop-design](https://github.com/mcanco/My-Challanges/assets/94782375/b27803a8-0162-4c12-b632-107bc2c1c3dc)
![mobile-design](https://github.com/mcanco/My-Challanges/assets/94782375/79246421-fae7-42ea-b823-345d21c8ace5)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- CSS
- Flexbox
- CSS Grid
- Media Query

### What I learned
 
I had the pleasure to learn and have more understanding of the use of the div element in HTML. Appreciated the easeness in styling the div element and it's inside elements.
 
Also, I learned the basics of CSS syntax. The use of CSS selectors to target HTML elements, centering elements, adding background images and colors, styling buttons and links.

To view code snippets, see below:

```html
  <div class="main">
        <img class="hero-img" src="./images/illustration-hero.svg" alt="">

        <h1>Order Summary</h1>
        <p id="summary">You can now listen to millions of songs, 
             audiobooks, and podcats on any device 
             anywhere you like!
        </p>

        <div class="plan"> 
            <img src="./images/icon-music.svg" alt="icon-music">
            <p ><span>Annual Plan</span><br>$59.99/year</p>
            <a id="change" href="#">Change</a>
        </div>

        <button type="submit">Proceed to Payment</button>
        
        <a id="cancel-order" href="#">Cancel Order</a>
    </div>
```
```css
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

html body {
    background-image: url(./images/pattern-background-desktop.svg);
    background-size: contain;
    background-repeat: no-repeat;
    background-color: hsl(225, 100%, 94%);
    font-size: 16px;
}
.hero-img {
    width: 500px;
    border-radius: 20px 20px 0px 0px;
}
.main {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #fff;
    max-width: 500px;
    margin: 40px auto;
    border-radius: 20px;

}
h1 {
    margin: 25px 0px 10px 0px;
    color: hsl(223, 47%, 23%);
    text-align: center;
}
#summary {
    width: 310px;
    text-align: center;
    color: hsl(224, 23%, 55%);
    line-height: 1.4;
}
.plan {
    background-color: hsl(225, 100%, 98%);
    border-radius: 15px;
    margin: 15px 45px;
    padding: 20px;
    width: 410px;
    height: 85px;
    display: grid;
    grid-template-columns: 4.5rem auto auto;
    align-items: center;
}
.plan span {
    font-weight: bold;
    color: hsl(223, 47%, 23%);
}
#change {
    color: hsl(245, 75%, 52%);
    text-align: end;
    padding-right: 10px;
}
#change:hover {
    color: hsl(224, 23%, 55%);
    text-decoration: none;
}
button {
    background-color: hsl(245, 75%, 52%);
    margin: 5px 45px;
    width: 410px;
    height: 35px;
    border-radius: 7px;
    border: none;
    color: #fff;   
}
button:hover {
    background-color: hsl(224, 23%, 55%);
    cursor: pointer;
}
#cancel-order{
    color: hsl(224, 23%, 55%);
    margin: 20px 0px 35px 0px;
    text-decoration: none;
}
#cancel-order:hover {
    color: hsl(223, 47%, 23%);
}
@media screen and (max-width: 768px) {
    html, body {
        background-image: url(./images/pattern-background-mobile.svg);
        background-repeat: no-repeat;
        background-size: auto;
        background-color: hsl(225, 100%, 94%);
    }
    .hero-img {
        width: 375px;
    }
    .main {
        width: 375px;
        margin: 20px auto;
    }
    #summary{
        width: 240px;
    }
    .plan {
        width: 325px;
    }
    button {
        height: 40px;
        width: 325px;
    }
    
}
```

### Continued development

  To further my leraning process, I would like to manipulate HTMl elements with the use of JavaScript(jQuery).
  
  Also, I would like to use some CSS elements such as positioning, float, pseudo-elements and animation.

### Useful resources

  - I mostly used *CSSNotesforProfessionals* book to tackle my struggles, and I would recommend to anyone with no home internet as reference guide.  

## Author

- Frontend Mentor - [@yourusername]([https://www.frontendmentor.io/profile/mcanco])


