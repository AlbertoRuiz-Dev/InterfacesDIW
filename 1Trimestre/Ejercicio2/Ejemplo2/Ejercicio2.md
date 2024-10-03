# 3.7.2. Ejercicio sobre usabilidad en formularios

## Descripción del ejercicio
En este ejercicio, se nos proporciona un fragmento de código HTML y CSS con varios errores de usabilidad y accesibilidad en un formulario. El objetivo es identificar y corregir estos errores para mejorar la experiencia del usuario y hacer el formulario más accesible.

## Problemas identificados

### 1. Etiquetas de texto sin el atributo `for`
Las etiquetas `<label>` no tienen el atributo `for`, lo que dificulta la asociación entre las etiquetas y los campos de entrada. Esto afecta la accesibilidad, ya que los usuarios de tecnologías asistivas no pueden identificar correctamente qué campo está relacionado con qué etiqueta.

### 2. Tamaño de fuente pequeño
El tamaño de la fuente es de 12px, lo cual puede ser difícil de leer, especialmente para usuarios con problemas de visión. Un tamaño de fuente mayor es recomendable para mejorar la legibilidad.

### 3. Tipo de campo incorrecto para el correo electrónico
El campo de correo electrónico está definido como `text` en lugar de `email`. Esto impide que el navegador valide correctamente la entrada del usuario y no ofrece teclados específicos para correos electrónicos en dispositivos móviles.

### 4. Tipo de campo incorrecto para el teléfono
El campo de teléfono también está definido como `text` en lugar de `tel`, lo que nuevamente afecta la validación automática y la accesibilidad en dispositivos móviles.

### 5. Estilo de botones y campos de entrada poco atractivo
El botón de envío y los campos de entrada tienen un estilo básico sin indicación visual cuando se interactúa con ellos. Esto puede reducir la experiencia de usuario, ya que no hay retroalimentación clara al enfocar o enviar el formulario.

## Soluciones propuestas

### 1. Incorporar el atributo `for` en las etiquetas
Se ha añadido el atributo `for` en cada `<label>`, asociándolas correctamente con su campo de entrada correspondiente mediante el atributo `id` en los campos de entrada.

```html
<label for="nombre">Nombre</label>
<input type="text" id="nombre" name="nombre" placeholder="Pon tu nombre aquí">
```
### 2. Estilo poco llamativo y mala colocacion de los label
- Se mejoró el diseño general del formulario con bordes redondeados, sombras y un fondo claro para destacar los elementos del formulario.
- Los campos de entrada y el botón de envío ahora tienen bordes redondeados y cambios de color al ser enfocados, mejorando la retroalimentación visual y proporcionando una mejor experiencia de usuario.
