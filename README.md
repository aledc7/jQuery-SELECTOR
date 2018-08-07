# jQuery/CSS SELECTOR
###### Resumen de los selectores mas útiles en Jquery, y su explicación.
###### Recordemos que JQuery comparte los selectores con CSS.

- [x] Ale DC
- [x] TFI-UAI


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
$("li:nth-child(1)")................#
$("li:nth-last-child(1)")................#
$("li:nth-of-type(2)")................#
$("li:nth-last-of-type(2)")................#
$("b:only-child")................#
$("h3:only-of-type")................#
$("div > p")................#
$("div p")................#
$("ul + p")................#
$("ul ~ table")................#
$("ul li:eq(0)")................#
$("ul li:gt(0)")................#
$("ul li:lt(2)")................#
$(":header")................#
$(":header:not(h1)")................#
$(":animated")................#
$(":focus")................#
$(":contains(Duck)")................#
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
