#validaFormPlugin2.js

Plugin que valida los controles de un formulario que tengan el atributo required = "true", añade estilos validate de bootstrap 3 para jsFramework.

<h2>Atributos</h2>

<b>min_width</b> = Valor de width minimo en entero o decimal que debe llevar la barra de progreso, esta en "em" Ej: 45em.
<br>
<b>icons</b> = Mostrar iconos, true/false.
<br>
<b>barra</b> = Mostrar barra, true/false.
<br>
<b>pariente</b> = que pariente usa dentro de los divs? 'grandpa','dad', usa los divs que contienen al control que se esta validando.


<h2>Set del Plugin</h2>

$("selector").validaForm('min_width',icons,barra,pariente);
