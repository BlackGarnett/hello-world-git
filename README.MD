# Cabeceras
# Cabecera h1 (1x#)
## Cabecera h2 (2x#)
### Cabecera h3 (3x#)
#### Cabecera h4 (4x#)
##### Cabecera h5 (5x#)
###### Cabecera h6 (6x#)

# Underlines
Underline 1 con (3x-)
---------------------

Underline 2 con (3x=)
=====================

# Emphasis
- Formato en *italica* con ( * ). 
- Formato en _italica_ con ( _ ).
- Formato en **bold** con ( 2x* ).
- Formato en __bold__ con ( 2x_ ).
- Formato en ~tachado~ con ( ~ ).
- Aquí podemos usar *formato italica*, pero también **bold** y ~tachado~.

# Listas
1. Esto es una item de Lista Ordenada.
2. Esto es una item de Lista Ordenada.
3. Esto es una item de Lista Ordenada.
- Esto es un item de Lista Desordenada.
- Esto es un item de Lista Desordenada.
- Esto es un item de Lista Desordenada.

# Links
- <a href="https://www.github.com" title="GitHub">Esto es un Link en HTML</a>.
- [Esto es un link en markdown](https://www.github.com).
- [Esto es un link en markdown a un archivo](index.html).

# Imágenes
![Logo GitHub](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon48.png)

# Code Snippets
- Código en JSON
``` json
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

- Código en JavaScript
``` javascript
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

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Juan   | Perez    | 12345678  |
| Pepe   | Rodríguez| 12345678  |

# Citas / Quotes
Esto es un texto referente a la siguiente cita:
> Esto es una cita con ( > ).

Esto es otro texto que no se relaciona con la cita anterior.
> Esto es otra cita.

# Líneas Divisoras
Esto es un texto que será dividido por guiones medios.

---
Esto es otro texto dividido por astericos.

***

Esto es otro texto dividido por guiones bajos.

___

# Saltos de línea
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo. 

Esto es nuestro tercer párrafo.
- Lista