# jQuery/CSS SELECTOR

[<img src="https://github.com/aledc7/PHP-Certification/blob/master/aledc-logo.png?raw=true">](https://aledc.com)

###### Resumen de los selectores mas útiles en Jquery, y su explicación.
###### Recordemos que JQuery comparte los selectores con CSS.

- [x] Ale DC
- [x] TFI-UAI
- [ ] SALUDOS A BILL GATES


```javascript
$("#Lastname")  ................# Selecciona cualquier elemento que tenga el id #Lastname
$(".intro")    ................#  Selecciona cualquier elemento con la clase .intro               
$(".intro, #Lastname")...........#  Selecciona cualquier elemento con la clase .intro y con el ID #Lastname        
$("h1")................# Selecciona todos los títulos que sean <h1>                       
$("h1, p")................# Selecciona todos los títulos que sean <h1> , y también los <p>arrafos                     
$("p:first")................# Selecciona el primer párrafo que encuentre              
$("p:last")................# Selecciona el último párrafo que encuentre
$("tr:even")................# Selecciona las filas pares en una tabla
$("tr:odd")................# Selecciona las filas impares en una tabla
$("p:first-child")................# selecciona todos los primeros parrafos que sean el primer hijo de sus padres.
$("p:first-of-type")................# selecciona a todos los primeros del mismo tipo, en este caso de parrafos.(can be others)
$("p:last-child")................# a la inversa que los dos anteriores, este selecciónará el último parrafo hijo
$("p:last-of-type")................# lo mismo que first-of-type pero el último.
$("li:nth-child(1)")................# Selecciona el primer elementos de cada lista que encuentre
$("li:nth-last-child(1)")................# Selecciona el ultimo elemento de cada lista que encuentre
$("li:nth-of-type(2)")................# Selecciona el segundo elemento de cada lista que encuentre
$("li:nth-last-of-type(2)")................# Selecciona el Anteúltimo elemento de cada lista que encuentre
$("b:only-child")................# todos los elementos que estén en negrita y sean el unico hijo del padre.
$("h3:only-of-type")................# todos los elementos de clase <h3> que sean el unico elemento h3 de su padre
$("div > p")................# Selecciona todos los <P>arrafos que estén dentro de algun DIV y sean hijos directos
$("div p")................# Similar al anterior, nada mas que pueden no ser hijos directos.
$("ul + p")................# Selecciona todos los Parrafos que estén al lado de un elemento Lista
$("ul ~ table")................# Selecciona todas las tablas que tengan una lista ul dentro.
$("ul li:eq(0)")................# Selecciona un elemento de una lista, por el índice, el indice arranca en cero.
$("ul li:gt(0)")................# Selecciona todos los elementos de una lista que sean mayor que cero
$("ul li:lt(2)")................# Selecciona todos los elementos de una lista con un indice menor que 2
$(":header")................# Selecciona los elementos considerados heders, que son <h1> y <h2>
$(":header:not(h1)")................# Igual que el anterior, selecciona todos los headers pero no selecciona los <h1>
$(":animated")................# PENDIENTE
$(":focus")................# Selecciona el input en donde esté parpadeando el cursor
$(":contains(Duck)")................# Seleccionará cualquier elemento que contenga el texto Duck, sea o no un ID.
$("div:has(p)")................# Selecciona cualquier DIV que tenga un parrafo.
$(":empty")................# Seleccionará todos los elementos que esten vacíos, o sea no esten seteados, muy útil.
$(":parent")................# Selecciona todos los elementos que son padres de alguien. o sea se selecciona todo onda $("*")
$("p:hidden")................# Si existiera un campo oculto, lo seleccionará igual.
$("table:visible")................# Seleccionará todas las tablas que sean visibles
$(":root")................# Selecciona todo, no me queda claro cual es la diferencia de $("*")
$("p:lang(it)")................# Seleccionará todos los párrafos que tengan seteado el lenguaje it de italiano, otros: es, en
$("[id]")................# Seleccionará todos los elementos que tengan seteado algún id cualquiera sea.
$("[id=my-Address]")................# Selecciona por ID, parece similar a $("#Lastname")
$("p[id!=my-Address]").............# Selecciona todos los parrafos que NO tengan el id específico, lo niega con un signo !
$("[id$=ess]")................# usa el signo peso como comidin, seleccionará cualquier id que termi e en  "ess", muy útil.
$("[id|=my]")................# seleccionaría todos los elementos con un id que empiece por my y lego tenga un guión "my-"
$("[id^=L]")................# Selecciona todos los elementos con una id que empiece con L mayúscula
$("[title~=beautiful]")................# Selecciona todos los parrafos que tengan seteado un título. Es ese texto que se muestra cuando dejas el mouse posado. Se declara <p title="aledc"> </p>  
$("[id*=s]")................# Usa el comdin asterizco, esto seleccionara cualquer elemento con id que contenga una letra s
$(":input")................# Selecciona todos los objetos que sean input type
$(":text")................# Selecciona todos los elementos que sean del tipio text
$(":password")................# Selecciona los input que sean de password
$(":radio")................# Selecciona los radiobutons
$(":checkbox")................# selecciona los checkbox
$(":submit")................# Selecciona el boton de tipo Submit (muy util)
$(":reset")................# Selecciona el boton de tipi reset
$(":button")................# Selecciona todos los botones.
$(":image")................# Selecciona todos los elementos del tipo imágen
$(":file")................# Selecciona los campos del tipo "selecionar archivo"
$(":enabled")................# Selecciona todos los elementos habilitados del html
$(":disabled")................# Selecciona todos los elementos deshabilitados del html
$(":selected")................# Selecciona la opcion elegida en una lista desplegable
$(":checked")................# Selecciona checkbox checkeados y radiobutons seleccionados
$("*")................#  Selecciona todos los elementos del HTML

by Ale DC
```

###### Para entender a fondo, recomiendo esta herramienta Visual de los muchachos de la W3School

[Herramienta Seleccion](https://www.w3schools.com/jquery/trysel.asp)





