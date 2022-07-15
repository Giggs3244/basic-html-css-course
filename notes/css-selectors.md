# CSS Selectors

## Selector descendiente - descendant selector

footer p {}

Se usa para establecer estilos en los descendientes de un elemento, en este caso se seleccionan todas las p descendientes (que estan dentro) de un elemento footer.

se pueden combinar los selectores por ejemplo

article header p {}

los estilos seran aplicados unicamente a los elementos p que son hijos de los elementos header y donde header es hijo de elemento article

## Id Selector

`#author {}`

usando el selector de id se estableceran los estilos a los elementos que tienen el id author

```html
<p id="author"></p>
```

## Class Selector

`.nameClass {}`

usando el selector de clase se estableceran los estilos a los elementos que tienen la clase nameClass

```html
<p class="nameClass"></p>
```
