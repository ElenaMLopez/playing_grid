# GRID LAYOUT

### Introducción:

La definición habitual de Grid Layout, es que es un sistema de rejilla en dos dimensiones, y que se suele comparar con FlexBox que se trabaja en una dimensión. En Flex Box se les dice a los items que hacer en el eje horizontal y en el vertical, pero no se manejan ambos ejes al mismo tiempo. En ese caso los items que no caben en una linea pasan a la de abajo, lo que no quiere decir que en realidad se estén controlando.

Con Grid sí hacemos eso, tenemos el control de ambas dimensiones. Podemos determinar la posición tanto vertical como horizontal de un item.

Surgen una serie de preguntas:

- Voy a poder colocar los items Dónde quiera, pero habrá items que se coloquen solos.
- Se puede hacer lo mismo de muchas formas, pero no todas hace exactamente lo mismo, puesto que determinadas propiedades se comportan de forma distinta si el item no tiene sitio por ejemplo.
- Controlar las 2 dimensiones, no es Flexbox.
la colocación de los items es muy libre, no es una tabla al uso. 
- Tiene una sintaxis muy extensa.
- Es un poco locura controlar bien Grid, pero va a cambiar el css para siempre.

¿Se puede usar con cualquier framework?
En principio sí, porque es una especificación de CSS.

### Conceptos básicos:

![Grid Basis](images/grid_basis.png)

La base de Grid son las líneas, horizontales para las filas, y verticales para las columnas.
