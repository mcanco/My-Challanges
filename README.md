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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

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
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.
<!-- 
I had the pleasure to learn and have more understanding of the use of the div element in HTML. Appriciated the easeness in styling the div element and it's inside elements.
 
Also, I learned the basics of CSS syntax. The use of CSS selectors to target HTML elements, centering elements, adding background images and colors, styling buttons and links
 -->

To see how you can add code snippets, see below:

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

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development
<!-- 
  To further my leraning process, I would like to manipulate HTMl elements with the use of JavaScript(jQuery).
  
  Also, I would like to use some CSS elements such as positioning, float, pseudo-elements and animation.
 -->

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources
<!-- 
  - I mostly used *CSS Notes for Professionals* book to tackle my struggles, and I would recommend to anyone with no home internet as reference guide.  
 -->

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**


**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
