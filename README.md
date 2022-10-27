# Site para uma escola de skate - SkatePark

Este é um site para uma escola de skate, projetado e desenvolvido durante o [Gama Experience - 44](https://gama.academy).

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

![Screenshot_2](https://user-images.githubusercontent.com/105292489/198309361-a9b85e8b-8fff-472e-a538-7167428a0450.jpg)
![Screenshot_3](https://user-images.githubusercontent.com/105292489/198309593-bf2e1bda-23dc-4e64-b4dc-33f018f7c417.jpg)

### Links

- Solution URL: [Here](https://github.com/muryllohenriq/SkatePark)
- Live Site URL: [Here](https://muryllohenriq.github.io/SkatePark/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- JavaScript
- Bootstrap

### What I learned

```html
<h1>Esse foi o meu primeiro projeto utilizando o bootstrap.</h1>
<section
      class="d-flex align-items-center py-5"
      style="
        min-height: 60vh;
        background: linear-gradient(
            0deg,
            rgba(0, 0, 0, 0.2),
            rgba(0, 0, 0, 0.2)
          ),
          url(./imgs/skate-virado.jpg);
        background-position: center center;
        background-size: cover;
      "
    >
      <div class="container text-center">
        <h2 class="display-3 mb-3 text-light fw-bold">
          "O skate é a base da liberdade..."
        </h2>
        <p class="text-light fw-bold">KarenStuart</p>
      </div>
    </section>
<h1>A forma como o bootstrap trabalha com imagens e o display flex é realmente muito intuitivo e prático.</h1>
```
```css
.proud-of-this-css {
  color: #00a4ff;
}
```
```js
// Example starter JavaScript for disabling form submissions if there are invalid fields
(() => {
    'use strict'
  
    // Fetch all the forms we want to apply custom Bootstrap validation styles to
    const forms = document.querySelectorAll('.needs-validation')
  
    // Loop over them and prevent submission
    Array.from(forms).forEach(form => {
      form.addEventListener('submit', event => {
        if (!form.checkValidity()) {
          event.preventDefault()
          event.stopPropagation()
        }
  
        form.classList.add('was-validated')
      }, false)
    })
  })()
```
### Continued development

Talvez criar mais uma página introduzindo as pistas disponíveis.

### Useful resources

- [Resource 1](https://www.markdownguide.org) - Esse artigo me ajudou muito com o read-me.
- [Resource 2](https://getbootstrap.com) - Documentação do Bootstrap.

## Author

- Website - [muryllohenriq](https://github.com/muryllohenriq)
- Frontend Mentor - [@muryllohenriq](https://www.frontendmentor.io/profile/muryllohenriq)
- LinkedIn - [Muryllo Henrique](https://www.linkedin.com/in/muryllohenrique/)

## Acknowledgments

Gostei bastante da praticidade que o bootstrap traz e da facilidade na manipulação dos elementos, pretendo continuar utilizando-o e construindo mais sites bonitos e práticos como este.
