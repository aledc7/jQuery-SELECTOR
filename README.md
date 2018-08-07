# jQuery/CSS SELECTOR
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
$("div:has(p)")................#
$(":empty")................#
$(":parent")................#
$("p:hidden")................#
$("table:visible")................#
$(":root")................#
$("p:lang(it)")................#
$("[id]")................#
$("[id=my-Address]")................#
$("p[id!=my-Address]")................#
$("[id$=ess]")................#
$("[id|=my]")................#
$("[id^=L]")................#
$("[title~=beautiful]")................#
$("[id*=s]")................#
$(":input")................#
$(":text")................#
$(":password")................#
$(":radio")................#
$(":checkbox")................#
$(":submit")................#
$(":reset")................#
$(":button")................#
$(":image")................#
$(":file")................#
$(":enabled")................#
$(":disabled")................#
$(":selected")................#
$(":checked")................#
$("*")
```
