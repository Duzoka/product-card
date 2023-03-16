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
![desktop-preview](https://user-images.githubusercontent.com/102036752/222904104-bfe3b7ba-418f-45a3-9f45-351c45685a25.jpg)

<table>

 <thead> <th>Desktop Design</th> <th>Mobile Design</th> <th>Active Stats</th> </thead>
 <tbody> 
 
 <tr> 
 <td> <img src="https://user-images.githubusercontent.com/102036752/222904335-8f05d385-7ccf-4b81-b30b-dc6c48eb70d4.jpg" alt="desktop preview">
</td>
 <td> <img src="https://user-images.githubusercontent.com/102036752/222904346-26d1dc41-1e0b-44a6-af65-0f863356da51.jpg" alt="Mobile preview">
</td>
 <td> <img src="https://user-images.githubusercontent.com/102036752/222904355-0b91142f-f050-40ad-8de4-8c2c2936d049.jpg" alt="Active stats preview">
</td>
 <tr>
 
 </tbody>

</table>


### Screenshot

<table>

 <thead> 
    <th>Desktop Screenshot</th>
    <th> Mobile Screenshot</th> 
 </thead>
 <tbody>
  <tr> 
    <td>
      <img src="https://user-images.githubusercontent.com/102036752/222905856-09e43a66-cfe4-4609-81eb-a6cdb7ab074e.png">
   </td>
    <td>
      <img src="https://user-images.githubusercontent.com/102036752/222904655-63ec618f-9190-4e93-9c9d-41b8dcacfb13.png" alt="mobile screenshot">
    </td>
   </tr>
 </tbody>

</table>


### Links

- Solution URL: [Frontend Mentor Solution]https://www.frontendmentor.io/solutions/product-card-made-with-html-and-css-TzOiwwIkOe)
- Live Site URL: [Product Card](https://duzoka.github.io/product-card/)

## My process

### Built with

- HTML5
- CSS 

### What I learned


```css
.card {
    
    overflow: hidden;
}

.img-section img {
    object-fit: cover;
}
```

```html

<picture>
    <source media="(max-width: 695px )" srcset="./src/images/image-product-mobile.jpg">
    <source media="(min-width: 700px )" srcset="./src/images/image-product-desktop.jpg">
    <img src="./src/images/image-product-desktop.jpg" alt="perfume">
</picture>

```

### Continued development

Never give up. Just stay determined and strong on the way. Go ahead and do projects. :)

### Useful resources

- [ChatGPT](https://openai.com/blog/chatgpt/) - I've used ChatGPT to learn HTML and CSS. It help me alot


## Author

- Frontend Mentor - [@Duzoka](https://www.frontendmentor.io/profile/Duzoka)


## Acknowledgments

ChatGPT send to you an embrance! And also this guy have helped my in Frontend Mentor: [Her profile in Frontend Mentor](https://www.frontendmentor.io/profile/0xAbdulKhalid). 
