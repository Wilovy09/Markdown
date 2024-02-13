# Cosas que se pueden hacer con Markdown y Github

## Titulos

`# Hola` = `<h1>Hola</h1>`

`## Hola` = `<h2>Hola</h2>`

`### Hola` = `<h3>Hola</h3>`

`#### Hola` = `<h4>Hola</h4>`

`##### Hola` = `<h5>Hola</h5>`

`###### Hola` = `<h6>Hola</h6>`

## Efectos de texto

`_Italic_` = _Italic_

`**STRONG**` = **Strong**

`~~TACHADO~~` = ~~Tachado~~

## Ul ó Unordered list

```md
- Elemento 1
  - Elemento 2
- Elemento 3
- Elemento 4
```

Es igual a:

- Elemento 1
  - Elemento 2
- Elemento 3
- Elemento 4

## Ol ó Ordered List

```md
1. Elemento 1
   1. Sub-Elemento 1
2. Elemento 2
3. Elemento 3
```

Es igual a:

1. Elemento 1
   1. Sub-Elemento 1
2. Elemento 2
3. Elemento 3

## Enlaces

`[GITHUB MARKDOWN](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)`

Es igual a:

[GITHUB MARKDOWN](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

`[GITHUB MARKDOWN](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "CUSTOM TITTLE")`

Es igual a:

[GITHUB MARKDOWN](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "CUSTOM TITTLE")

## Citas

`> THIS IS A QUOTE`

> THIS IS A QUOTE

## HR

`---`

---

## Código

```
print("Hello World")
```

```py
print("Hello World")
```

```html
<h1>Hello World</h1>
```

## Tablas

```md
|TEST   |PRUEBA |
|-------|-------|
|Hola   |Hello  |
```

Es igual a:

|TEST   |PRUEBA |
|-------|-------|
|Hola   |Hello  |

## Imagenes

`![visual studio code logo](https://www.wilovy.com/favicon.svg "VS CODE LOGO")`

Es igual a:

![visual studio code logo](https://www.wilovy.com/favicon.svg "VS CODE LOGO")

`![visual studio code logo](./img/favicon.svg "VS CODE LOGO")`

Es igual a:

![visual studio code logo](./img/favicon.svg "VS CODE LOGO")

## GITHUB MARKDOWN

### @

@Wilovy09

### Checkbox

* [x] Task 1
* [ ] Task 2
* [x] Task 3

### Emojis

:smiley:

### Avisos

```md
> [!NOTE]
> Esto es una nota
```

> [!NOTE]
> Esto es una nota

---

```md
> [!TIP]
> Esto es una consejo
```

> [!TIP]
> Esto es una consejo

---

```md
> [!IMPORTANT]
> Esto es algo importante
```

> [!IMPORTANT]
> Esto es algo importante

---

```md
> [!WARNING]
> Esto es una advertencia
```

> [!WARNING]
> Esto es una advertencia

---

```md
> [!CAUTION]
> Precausión con esto
```

> [!CAUTION]
> Precausión con esto

## LaTex

Podemos usar sintaxis de LaTex en Markdown

### Ecuaciones de linea

`$ ecuacion $`

$ x^{3} + x^{-3} $

### Ecuaciones en bloque

`$$ ecuacion $$`

$$ x^{3} + x^{-3} $$

## Fracciones

`\frac{numerador}{denominador}`

$$ \frac{1}{2} $$

## Exponentes

`x^{n}`

$$ x^{n} $$

## Raíz cuadrada o n

`\sqrt{x}`

$$ \sqrt{16} $$

`\sqrt[n]{16}`

$$ \sqrt[n]{16} $$

## Integral definida

`\int_{a}^{b} f(x) dx`

$$ \int_{a}^{b} f(x) dx $$

## Sumaroria

`\sum_{i+1}^{n} a_i`

$$ \sum_{i+1}^{n} a_1 $$

## Producto

`\prod_{i+1}^{n} a_i`

$$ \prod_{i+1}^{n} a_i $$

## Funciones trigonométricas

`\sin(x)`

$$ \sin(x) $$

`\cos(x)`

$$ \cos(x) $$

`\tan(x)`

$$ \tan(x) $$

## Subindices y superindices

`a_{ij}`

$$ a_{ij} $$

`b^{2}`

$$ b^{2} $$

## Espacios

Podemos simplemente poner un " " entre los terminos pero podemos poder más espacio con lo siguiente

$$ b^{2} + b^{2} $$

### Espacio fino

`\,`

```md
$$ b^{2}\,+\,b^{2} $$
```

$$ b^{2}\,+\,b^{2} $$

### Espacio medio

`\:`

```md
$$ b^{2}\:+\:b^{2} $$
```

$$ b^{2}\:+\:b^{2} $$

### Espacio ancho

`\;`

```md
$$ b^{2}\;+\;b^{2} $$
```

$$ b^{2}\;+\;b^{2} $$
