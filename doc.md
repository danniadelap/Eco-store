// Declaracion de variables

// $primary-color: blue;
// $secondary-color: green;
// $tertiary-color: purple;

// default flag
// Se encarga de asignar un valor a la variable si
// y solo si esa variable no esta definida o 
// su valor es null

At-rules

@use: importa, modulos estilos y funciones de otras hojas de estilos. la diferencia con @import es que import se encarga de hacer los estilos globales.

@function: permite crear funciones personalizadas, sin embargo Sass cuenta con funciones ya existentes.

@forward: Recibe como parametro una URL y nos ayuda a cargar los estilos de nuestra hoja de estilos, es muy importante hacer uso de @use para que los modulos esten disponibles en nuestra hoja de estilos.

@extend: tiene que ver con el concepto de herencia.

@at-root: se encarga de cargar nuestros estilos en el root del css.

@include: nos ayuda a invocar los mixins.

@error, @warn @debug: sirver para cuando hay un error, una advertencia o se quiere debugear, respectivamente

@for, @if, @each, @while: tienen que ver con estructuras de control, se pueden usar dentro de una función