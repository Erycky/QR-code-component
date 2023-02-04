# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./solution/QR-CODE%20Solution.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

First I created a container with 100vh and 100vw, I used it to center the card in the middle of the screen, after that I styled the card, it was not necessary @mediaqueries because flexbox was used for styling, and one of the benefits is that it makes it good part of the design in responsive.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS variables on :root
- Flexbox

### What I learned

In this practical challenge I learned semantics in images, with the "alt" attribute and how to use :root to store colors and thus facilitate styling.

```html
<img src="./images/image-qr-code.png" alt="QR-Code">
```
```css
:root {
    --white: hsl(0, 0%, 100%);
    --light-gray: hsl(212, 45%, 89%);
    --grayish-blue: hsl(220, 15%, 55%);
    --dark-blue: hsl(218, 44%, 22%);
}
```

### Useful resources

- [Flexbox Guide](https://origamid.com/projetos/flexbox-guia-completo/) - It helped me in Flexbox. This guide is good for remembering concepts and good usage practices.

## Author

- Website - [Erycky Rayner Developer](https://erycky.github.io/Erycky-Front-End-Dev/)
- Frontend Mentor - [@Erycky](https://www.frontendmentor.io/profile/Erycky)
- Instagram - [@mozardino](https://www.twitter.com/yourusername)

## Acknowledgments

Thanks to André Rafael, from Origamid, who is and remains a great teacher in my journey as a web developer.