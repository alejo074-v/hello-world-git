# Version del Curso
Version Actual: V1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# underline
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** primer forma.
- formato __bold o strong__ segunda forma.
- formato ~~tachado~~, formato normal.

# Listas
1. Esto es un item de lista desordenada
2. Esto es un item de lista desordenada
3. Esto es un item de lista desordenada

- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
-[Esto es un link al index](index.html)

# Imagenes
![Logo de Github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snippets
Codigo en JSON

```JavaScript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```
Codigo con JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

# Tablas
|Nombre|Apellido|Documento|
|------|--------|---------|
|Maxi  |Burgos  |345635453|
|Tomas |Pineda  |1565434  |

# Citas
Est es un texto referente a una cita
> Esto es una cita

Est es un texto referente a otra cita
> Esto es otra a una cita

# Lineas Divisoras
Esto es un texto que sera dividido por guiones medios..

---
Esto es otro texto que es dividido por asteriscos.

***

Esto es otro texto dividido por guiones bajos

___

# Saltos de Lineas
Esto es nuestro primer parrafo

Esto es nuestro segundo parrafo

Esto es nuestro tercer parrafo