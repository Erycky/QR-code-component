# Frontend Mentor - Solução Componente QR-Code

Esta é uma solução para o [QR code component challenge no Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação criando projetos realistas.

## Índice

- [Visão Geral](#visão-geral)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Feito com](#feito-com)
  - [O que aprendi](#o-que-aprendi)
  - [Recursos úteis](#recursos-úteis)
- [Autor](#autor)
- [Agradecimentos](#agradecimentos)

## Visão Geral

### Screenshot

![](./solution/QR-CODE%20Solution.png)

### Links

- Solução URL: [https://github.com/Erycky/QR-code-component](https://github.com/Erycky/QR-code-component)
- Site URL: [https://erycky.github.io/QR-code-component/](https://erycky.github.io/QR-code-component/)

## Meu processo

Primeiro criei um container com 100vh e 100vw, usei para centralizar o cartão no meio da tela, depois estilizei o cartão, não foi necessário @mediaqueries pois o flexbox foi usado para estilizar, e um dos benefícios é que transforma boa parte do design em responsivo.

### Feito com

- HTML5 semântico
- CSS
- CSS com variaveis no :root
- Flexbox

### O que aprendi

Nesse desafio prático aprendi semântica nas imagens, com o atributo "alt" e como usar :root para armazenar cores e assim facilitar a estilização.

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

### Recursos úteis

- [Flexbox Guide](https://origamid.com/projetos/flexbox-guia-completo/) - Isso me ajudou no Flexbox. Este guia é bom para relembrar conceitos e boas práticas de uso.

## Autor

- Website - [Erycky Rayner Portfólio](https://erycky.github.io/Erycky-Front-End-Dev/)
- Frontend Mentor - [@Erycky](https://www.frontendmentor.io/profile/Erycky)
- Instagram - [@mozardino](https://www.instagram.com/mozardino/)

## Agradecimentos

Agradeço ao André Rafael, da Origamid, que é e continua sendo um grande professor na minha jornada como desenvolvedor web.

### English version

# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./solution/QR-CODE%20Solution.png)

### Links

- Solution URL: [https://github.com/Erycky/QR-code-component](https://github.com/Erycky/QR-code-component)
- Live Site URL: [https://erycky.github.io/QR-code-component/](https://erycky.github.io/QR-code-component/)

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

- Website - [Erycky Rayner Portfólio](https://erycky.github.io/Erycky-Front-End-Dev/)
- Frontend Mentor - [@Erycky](https://www.frontendmentor.io/profile/Erycky)
- Instagram - [@mozardino](https://www.instagram.com/mozardino/)

## Acknowledgments

Thanks to André Rafael, from Origamid, who is and remains a great teacher in my journey as a web developer.
