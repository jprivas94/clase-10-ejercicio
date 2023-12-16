1. Definicion de Responsive Web Design
   Responsive Web Design es una técnica de desarrollo que asegura que los sitios web se adapten y funcionen eficientemente en diversos dispositivos, manteniendo una experiencia de usuario ideal enfocandose desde mobile o desktop.
2. Enfoques principales
   Los enfoques principales del Responsive Web Design incluyen diseño fluido, uso de media queries garantizando adaptabilidad y consistencia en distintos dispositivos.
3. Definicion de break points
   Son los puntos predefinidos en el ancho de la pantalla donde el diseño web responde con cambios estructurales y de estilo para adaptarse.
4. Ejemplo de Enfoque Mobile First
   Para utilizar mobile first se utiliza min-width
   @media (min-width: 600px){
   background-color: red;

} 5. Ejemplo de Ejemplo Deskop First
Para utilizar desktop first se utiliza max-width
@media (max-width: 1040px){
background-color: blue;
} 6. Buenas practicas y que cosas no se debe hacer en el responsive web design con los break points y enfoques.
1.-Utilizar los media querys en orden de mayor a menor
2.-No combinar min-width y max-width
