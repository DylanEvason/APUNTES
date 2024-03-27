## LISTAS
<ul>
    <li><a href="#UL">UL</a></li>
    <li><a href="#OL">OL</a></li>
    <li><a href="#DL">DL</a></li>
    <li><a href="#ListasAni">Listas anidadas</a></li>
</ul>

Sirven para listar contenido. En función del tipo de contenido de nuestra lista, tenemos tres tipos de listas:

## UL
Unordered list
Cuando el orden de la lista no afecta (ejemplo: lista de compra).

## OL
Ordered list
Cuando el orden de la lista es importante (ejemplo: manual de lego).

## DL
Definition list
Se utilizan para hacer una lista de definiciones (ejemplo: Diccionario).

---

## HTML

<span id="UL"></span>

### UL

Para crear una lista desordenada en HTML es con lo siguiente:
```html
<ul>
    <!-- LI es "list item" -->
    <li>Pan</li>
    <li>Mantequilla</li>
    <li>Huevos</li>
    <li>Foxy</li>
</ul>
```

Esta es tu visualisación en la web:
<img src="/assets/HTML/ul1.png">

La forma más común para utilizar estas UL, son en los menús de las páginas web.
<img src="/assets/HTML/ul2.png">

<span id="OL"></span>

### OL
Para crear una lista ordenada en HTML es practicamente la misma que las UL:
```html
<h2>LISTA DE GANADORES</h2>
<ol>
    <li>Juanito</li>
    <li>Pedrito</li>
    <li>Maritza</li>
</ol>
```
<img src="/assets/HTML/OL1.png">

<span id="DL"></span>

### DL 
Las definition list tienen dos etiquetas para su uso:
<ul>
    <li>dt</li>
    <li>dd</li>
</ul>

Ejemplo:
```html
<dl>
    <dt>HTML</dt>
    <dd>HyperTex Markyp Lenguaje</dd>
</dl>
```
En página:
<img src="/assets/HTML/Dl1.png">

<span id="ListasAni"></span>

## LISTAS ANIDADAS
Existe la posibilidad de poner ul y ol dentro de las mismas constantemente. Puedes anidar todas las listas posibles, siempre y cuando sean necesarias para tu página web.

## ATRIBUTOS

### OL
type: estilo de numeración (1,A,a,I,i)
start: Inicio de las secuencias (un número)

### UL
type: Estilo de los items (disc, square, circle)
Pero en CSS estas posibilidades aumentan exponencialmente.