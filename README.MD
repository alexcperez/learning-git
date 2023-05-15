# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Undeline
Underline 1
-----------

Underline 2
===========

# Formato de Enfasis
- Formato *itálica* de la 1era forma.
- Formato _itálica_ de la 2da forma.
- Formato **bold** de la 1era forma.
- Formato __bold__ de la 2da forma.
- Formato ~~tachado~~.

# LISTAS
1. Esto es un Item de lista ordenada.
2. Esto es un Item de lista ordenada.
3. Esto es un Item de lista ordenada.
- Esto es un Item de lista desordenada.
- Esto es un Item de lista desordenada.
- Esto es un Item de lista desordenada.

# LINKS
- <a href="http://google.com">Enlace a Google</a>
- [Esto es un Link en Markdown](http://google.com)
- [Esto es un Link a Index](index.html)

# IMAGENES
![Logo Github](https://global-uploads.webflow.com/5f5a53e153805db840dae2db/6073fbf151fa4565d48572dc_GitHub_aprender-programaci%25C3%25B3n.jpeg)

# CODE SNIPPETS
Código en JSON
``` JSON
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
Código en javascript
```
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

# TABLAS
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Alex | Cantos | 123456 |
| Arturo | Pérez | 654321 |

# CITAS 
Esto es un Texto referente a una cita que ubicaremos al final:
> Esto es una **cita**

Esto es otro texto
> Cita #2

# LINEAS HORIZONTALES (DIVISORES)
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit (CON UN ENTER DE SEPARACION Y 3 GUIONES)

---

Lorem Ipsum is simply dummy text of the printing and typesetting industry (CON UN ENTER DE SEPARACION Y 3 ***)

***

Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book (CON UN ENTER DE SEPARACION Y 3 _)

___

# SALTOS DE LINEAS
(1ER PARRAFO)Lorem Ipsum is simply dummy text of the printing and typesetting industry.

(2DO PARRAFO)Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.

(3ER PARRAFO)It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
- It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and
- more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum