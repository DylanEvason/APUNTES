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
<img src="https://cdn.discordapp.com/attachments/1211474050681933824/1211474065945137213/image.png?ex=65ee5425&is=65dbdf25&hm=57c0a180b0eecacd79b3e42f0a8c7a1d11b3eb5d352765ffe1b79f2d951ad651&">

---
## ¿Cómo se usa correctamente?

Debes seguir los números, no saltearte constante mente los h.
Es decir, no deberías usar un h4 sin antes haber tenido un h3, pero no puedes usar el h3 sin antes haber un h2, etc. <br>
<img src="https://cdn.discordapp.com/attachments/1211474050681933824/1211474859826356284/image.png?ex=65ee54e2&is=65dbdfe2&hm=78930b670cb365fa430020a88ea7962469236151a2498f279568095311c638dc&">

### EJEMPLO DE MDN
La MDN nos da un ejemplo de como usar correctamente los Hs para no cometer errores semanticos.
<img src="https://cdn.discordapp.com/attachments/1211474050681933824/1211475466343555103/image.png?ex=65ee5573&is=65dbe073&hm=ce35bb14359277ba047d4918c668973952d2321b47bde84dab9480c4190e194f&" width="450" height="auto">

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
<img src="https://cdn.discordapp.com/attachments/1211474050681933824/1211474550706016266/image.png?ex=65ee5498&is=65dbdf98&hm=6c4c2d423eaffd963da1482f3cbc6624d5152a58d67513b3097eb87b7a4e7e9a&" >

---

Fuentes:
>MDN: [Elementos títulos](https://developer.mozilla.org/es/docs/Web/HTML/Element/Heading_Elements)
