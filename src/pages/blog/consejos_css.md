---
layout: ../../layouts/BlogPostLayout.astro
title: Consejos de CSS
draft: false
date: 2022/03/16
short: ¿Te atascas dando formato a algunas de tus páginas? Revisa estos
 consejos que te doy a continuación.
---

CSS es un lenguaje de definición de estilo muy potente, pero también muy complejo
a menudo es complicado conseguir hacer lo que uno quiere. Es normal y no debes
frustrarte. Con la experiencia irás atinando.

![](https://media1.giphy.com/media/yYSSBtDgbbRzq/giphy.gif)

Lo mejor que puedes hacer es copiar cuando veas que algo te gusta. Para esto desde
Chrome y Edge puedes darle a inspeccionar elementos y te saldrán las reglas que hacen
posible obtener esos resultados.

Algunos recursos que te pueden resultar interesantes son:

- [Da estilo a tus títulos](http://cssdemos.tupence.co.uk/text-shadow.htm)
- [Ejemplos de animaciones](http://css3.bradshawenterprises.com/animations/)
- [Sliding de imágenes](http://css3.bradshawenterprises.com/sliding/)

Astro te permite trabajar de una forma avanzada con las hojas de estilo,
para conocer más detalles puedes consultar la [documentación del proyecto](https://docs.astro.build/en/guides/styling/)

## Algunos trucos:

### Dar espacio alrededor de un texto

Para genererar un texto con espacio alrededor.

<div class="example" style="padding: 1em">
Ejemplo
</div>

```css
p {
    padding: 1em;
}
```

<style>
.example {
    border: 1px dashed gray;
}
</style>

### Espacio después de un párrafo

Cada párrafo tiene

<div class="example">
    <p>Párrafo 1</p>
    <p>Párrafo 2</p>
</div>

```css
p {
    margin-bottom: 1em;
}
```

### Centrar un texto

Cada párrafo tiene

<div class="example" style="text-align: center">
    Texto centrado
</div>

```css
p {
    text-align: center;
}
```
