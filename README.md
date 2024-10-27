# E-commerce Ecológico Econia 🌱

*Econia* es un e-commerce ficticio de la venta de productos ecológicos. En donde los usuarios pueden encontrar desde cepillos de dientes y botellas reutilizables hasta shampoos y jabones sólidos, ofreciendo alternativas para reducir el impacto ambiental en la vida diaria.

## Objetivo
El objetivo es promover hábitos más sostenibles mediante productos que ayudan tanto al *planeta* como al *bienestar personal*, fomentando una vida cotidiana más consciente y saludable.

## Funcionalidades
- *Catálogo de productos ecológicos*: Opciones ideales para reemplazar artículos de uso diario.
- *Información adicional*: Consejos sobre el uso de los productos y sus beneficios.
- *Reseñas de usuarios*: Espacio para compartir experiencias con los productos y sugerencias hacia un consumo más ecológico .
- *Formulario de contacto*: Un espacio para resolver dudas y recibir aportes.

## Tecnologías Utilizadas
- *HTML5*
- *CSS*

## Descripción del proyecto
Este es un proyecto de *preentrega* para el curso de HTML y CSS en *Talentotech*. En la siguiente etapa del curso aprenderemos JavaScript, y con esos conocimientos planeo mejorar este e-commerce para darle más funcionalidad antes de la entrega final.

Este proyecto fue desarrollado con un enfoque en la responsividad, comenzando con un diseño optimizado para dispositivos móviles (400x600 px) y luego adaptándose a pantallas más grandes. A continuación, se detallan las características clave:

- *Encabezado y Navegación*: 
  - Utiliza *Grid* y *posición fija* para que el menú permanezca visible al desplazarse.
  - Implementa un menú hamburguesa (SVG) con un *input de tipo checkbox* para mostrar y ocultar opciones de navegación, junto con un ícono SVG para cerrar el menú.

- *Presentación de Productos*: 
    - Utiliza *Grid* para la disposición de las cards de productos. En pantallas grandes, las cards se distribuyen en filas de 3, 2 y 3.
- *Interacción con Productos*: 
    - Al hacer clic en el primer producto, que es *Shampoo*, el usuario es redirigido a una nueva pantalla. Esta pantalla está diseñada para mostrar el producto en detalle, con un botón para comprar y múltiples imágenes. La distribución en esta sección también se organiza utilizando Grid.

- *Reseñas*: 
  - Presentadas horizontalmente en dos filas, gracias a la implementación de *Grid*.

- *Formulario de Contacto*: 
  - Diseñado con *Formspree*, permite a los usuarios ingresar su nombre, correo y mensaje.

- *Redes Sociales*: 
  - Organizadas mediante *Flexbox* en el footer, asegurando una disposición ordenada de los enlaces uno al lado del otro.

- *Media Queries*: 
  - *Mid-Width de 850 píxeles*: Esta media query ajusta los márgenes laterales del main para proporcionar un mejor espaciado en pantallas intermedias.
  
  - *Mid-Width de 1,000 píxeles*: Se retira el menú hamburguesa y se distribuyen el nombre del e-commerce y el carrito de compras en los laterales. Además, el menú de navegación cambia a verse en la segunda fila con una disposición horizontal, con los enlaces dispuestos uno al lado del otro. Esto lo logre utilizando *Grid*. 
  - En las cards de productos, se modifica la disposición para mostrar filas de 3, 2 y 3. Las reseñas también se adaptan, permitiendo que dos reseñas se muestren una al lado de la otra, en una fila de dos columnas. Finalmente, el formulario de contacto se ajusta para que el área de texto sea más amplia.

*productos.html*
- *Media Query Mid-Width de 1,000 píxeles*: Se aplican cambios en la distribución del *Grid* para las imagenes.