# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
--------------
Underline 2
============

# Énfasis de los textos
- Itálica de la *Primer* forma 
- Itálica de la _Segunda_ forma 
- **Strong** de la primer forma 
- __Strong__ de la segunda forma
- ~~Tachado~~ de la unica forma

# Listas
## Lista ordenada
1. Item 1
2. Item 2
3. Item 3
4. Item 4
5. Item 5

## Lista desordenada
- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

# Links
## Forma tradicional
Se usa html normal <a href="https://google.com" target="_blank">Link</a>
## link en markdown
Se usa el link en [markdown](https://google.com)

# Imágenes
![Logo GitHub](https://w7.pngwing.com/pngs/914/758/png-transparent-github-social-media-computer-icons-logo-android-github-logo-computer-wallpaper-banner.png)

# Code snippets
Código en JSON
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
Código en javaScript
```javaScript
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
