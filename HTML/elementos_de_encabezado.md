# ELEMENTOS DE ENCABEZADO
## ¿Cuáles son los elementos de encabezado?
Simple, son los "h" van desde el h1 al h6, mientras menor categoría tenga, menos es su tamaño.

```html
    <!-- Los Hs -->
    <h1>HOLA GENTE</h1>
    <h2>HOLA GENTE</h2>
    <h3>HOLA GENTE</h3>
    <h4>HOLA GENTE</h4>
    <h5>HOLA GENTE</h5>
    <h6>HOLA GENTE</h6>
```
<img src="/assets/HTML/encabezados1.png">

---
## ¿Cómo se usa correctamente?

Debes seguir los números, no saltearte constante mente los h.
Es decir, no deberías usar un h4 sin antes haber tenido un h3, pero no puedes usar el h3 sin antes haber un h2, etc. <br>
<img src="/assets/HTML/encabezados2.png">

### EJEMPLO DE MDN
La MDN nos da un ejemplo de como usar correctamente los Hs para no cometer errores semanticos.
<img src="/assets/HTML/encabezados3.png" width="450" height="auto">

Esta es la forma como la resolví yo:
```html
    <body>
    <h1>Harry Potter</h1>
        <h2>Sinopsis</h2>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quo deserunt beatae dignissimos vero architecto reprehenderit quos ipsam cum! Repellat fugit recusandae esse nisi modi maiores saepe minus et similique nulla?</p>
        <h2>Novelas</h2>
            <h3>Harry Potter y la Piedra Filosofal</h3>
            <h3>Harry Potter y la Camara de los Secretos</h3>
            <h3>...</h3>
        <h2>Peliculas</h2>
            <h3>Harry Potter y la Piedra Filosofal</h3>
            <h3>Harry Potter y la Camara de los Secretos</h3>
            <h3>...</h3>
</body>
```
**Así se ve en la web** <br>
<img src="/assets/HTML/encabezados4.png" height="300" weith="auto">

---

Fuentes:
>MDN: [Elementos títulos](https://developer.mozilla.org/es/docs/Web/HTML/Element/Heading_Elements)
