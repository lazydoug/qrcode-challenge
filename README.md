# qrcode-challenge
Card layout QR code design with HTML and CSS


# Frontend Mentor - QR code component solution
This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents
- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview
This is my first challenge on Frontend Mentor. I took on this challenge so as to improve and test my skills as a aspiring Frontend Developer.

### Screenshot
- Solution screenshot: (./screenshot.png)

### Links
- Solution URL: (https://github.com/lazydoug/qrcode-challenge)
- Live Site URL: (https://lazydoug.github.io/qrcode-challenge/)

## My process

### Built with
- HTML
- CSS

### What I learned
I learned that the CSS center properties only work in flexboxes (i.e. the display property must be set to 'flex' for the parent element). Also the height of the parent element must be set to vertially align the child.


```html
<body>
  <div class="content">
    <h3 class="title">Improve your front-end skills by building projects</h3>
  </div>
</body>
```
```css
html, body {
  align-items: center;
  display: flex;
  justify-content: center;
  height: 100%;
  ...
}

.content {
  ...
  margin: auto;
  }
```

### Continued development
In this project, I was not very comfortable with centring divs in a parent element. Going forward, I would want to improve my understanding of that concept.

### Useful resources
- [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/Layout_cookbook/Center_an_element) - This helped me to understand how to center elements vertically in CSS.

## Author
- Linkedin - (https://www.linkedin.com/in/id-douglas/)
- Frontend Mentor - [@lazydoug](https://www.frontendmentor.io/profile/lazydoug)
