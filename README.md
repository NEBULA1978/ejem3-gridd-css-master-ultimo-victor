# ejem3-gridd-css-master-ultimo-victor

Este proyecto presenta una estructura HTML básica 
que utiliza CSS Grid Layout para organizar 12 cajas
en una cuadrícula. Los estilos CSS definen el diseño
de la cuadrícula y la presentación de las cajas,
a través de una media query. Los archivos HTML y 
CSS están vinculados para proporcionar la presentación deseada.

# Aprendiendo CSS Grid Layout

Este proyecto muestra un ejemplo básico de uso de CSS Grid Layout 
para organizar elementos en una cuadrícula. Se han utilizado archivos 
HTML y CSS para definir la estructura y estilos respectivamente.

## Estilos CSS

### Estilos generales para toda la página
Estos estilos definen la apariencia general de la página, como el color de fondo, 
la fuente y la alineación del texto. Por ejemplo:

```css
/* Estilos generales para toda la página */
body {
    background-color: antiquewhite;
    font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
    text-align: center;
}

    background-color establece el color de fondo para todo el cuerpo de la página, por ejemplo, antiquewhite.
    font-family define el tipo de fuente que se utilizará para el texto en la página.
    text-align alinea el texto en el centro de la página.

Estilos para el contenedor del diseño de rejilla

Aquí se establecen los estilos para el contenedor de la cuadrícula,
 definiendo su altura, colores de fondo, bordes y la configuración de la cuadrícula. Por ejemplo:

css

/* Estilos para el contenedor del diseño de rejilla */
.grid-layout {
    height: auto;
    display: grid;
    grid-template-areas: 'cabecera' 'menu' 'contenido' 'lateral' 'footer';
    grid-template-rows: auto;
    background-color: lightgreen;
    border: 1px solid black;
}

    height: auto define la altura del contenedor de la cuadrícula
 para que se ajuste automáticamente al contenido.
    display: grid especifica que este elemento actuará como una cuadrícula.
    grid-template-areas establece el diseño de la cuadrícula con
 áreas llamadas 'cabecera', 'menu', 'contenido', 'lateral' y 'footer'.
    grid-template-rows: auto hace que las filas de la cuadrícula se
 ajusten automáticamente a su contenido.
    background-color define el color de fondo de la cuadrícula.
    border agrega un borde de 1 píxel sólido y negro alrededor
 de la cuadrícula.

Estilos para los elementos de la rejilla (cajas)

Estos estilos se aplican a cada elemento dentro de la cuadrícula,
 como el diseño de borde,
 color de fondo, alineación de texto y relleno. Por ejemplo:

css

/* Estilos para los elementos de la rejilla (cajas) */
.caja {
    border: 4px solid black;
    background-color: lightgray;
    text-align: center;
    padding: 20px;
}

    border establece un borde de 4 píxeles, sólido y negro
 alrededor de cada caja.
    background-color define el color de fondo de cada caja.
    text-align centra el texto dentro de cada caja.
    padding agrega un relleno interno de 20 píxeles
alrededor del contenido de cada caja.

Estilos individuales para cada caja

Se asignan estilos específicos a cada caja individual en la
cuadrícula, definiendo su área
 dentro de la cuadrícula y su color de fondo. Por ejemplo:

css

/* Estilos individuales para cada caja */
.c1 {
    grid-area: cabecera;
    background-color: lightsteelblue;
}

    grid-area asigna la caja a un área específica de
 la cuadrícula, en este caso, 'cabecera'.
    background-color define el color de fondo específico
 para la caja 'c1', por ejemplo, lightsteelblue.

Estos estilos, aplicados a la estructura HTML proporcionada,
 generarán una cuadrícula con áreas
definidas y cajas visualmente distintas dentro de esas áreas.
