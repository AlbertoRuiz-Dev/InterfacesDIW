# 3.7.4. Ejercicio sobre usabilidad en el espaciado de los elementos

El siguiente fragmento de código HTML contiene varios errores relacionados con el espaciado de los elementos de texto, el menú de navegación y la tabla de datos. A continuación se detallan los problemas encontrados y las soluciones aplicadas.

## Problemas identificados

### 1. Espaciado insuficiente en los elementos de texto
-El texto original tenía un espaciado insuficiente entre líneas y párrafos, lo que afectaba la legibilidad del contenido.

### 2. Espaciado en el menú de navegación
-Los enlaces del menú de navegación estaban demasiado juntos, lo que hacía difícil la interacción del usuario y perjudicaba la estética.

### 3. Espaciado en la tabla de datos
-Las celdas de la tabla no tenían suficiente espacio, lo que hacía que los datos se vieran comprimidos y difíciles de leer.

## Soluciones propuestas

### 1. Espaciado en los elementos de texto
- Se ha aumentado el `line-height` a `1.6` y se han ajustado los márgenes de los párrafos y títulos para mejorar la legibilidad. Ahora el contenido es más fácil de leer y seguir visualmente.

### 2. Espaciado en el menú de navegación
- Se ha añadido espacio entre los enlaces del menú utilizando la propiedad `margin`. Además, el menú ha sido alineado al centro de la página para mejorar la disposición visual.

### 3. Espaciado en la tabla de datos
- Se ha añadido relleno (`padding`) a las celdas de la tabla para mejorar la separación entre los datos. Asimismo, se ha aplicado un color de fondo alternado en las filas usando `nth-child` para hacer más fácil el seguimiento visual de la información.
