# webappemergencias

Crear una  con una landing Page (index.html) para listar y seleccionar una emergencia/catastrofe específica, y una página detallada de la emergencia seleccionada (por ejemplo, incendios-amazonas-2022.html, terremoto-marruecos-2024.html, dana-valencia-2024.html), usando los conceptos vistos hasta ahora.

`Requisitos Generales`
1. Responsive Design: La página debe ser mobile-first, pero también debe adaptarse a dispositivos más grandes (computadoras de escritorio) utilizando media queries
2. Metodología BEM: Usar la metodología BEM para nombrar clases.
3. Etiquetas Semátnicas: Utilizar etiquetas HTML semánticas para estructurar el contenido.
4. Flexbox y centrado de elementos: Usar flexbox para crear el layout y centrar elementos según corresponda.
5. Links: Incluir enlaces a otras páginas dentro de la web, y enlaces externos (que se abran en una nueva pestaña).
6. Iframes: Insertar un mapa de Google Maps en la página de la catástrofe usando un iframe generado en la siguiente Web o con Google Maps: https://www.maps.ie/create-google-map/

## Parte 1: Landing Page (index.html)

`Instrucciones`

1. Crear una landingPage donde los usuarios puedan seleccionar la catástrofe que desean consultar.
2. Tarjeta de Catastrofe: Cada tarjeta debe contener:
Una imagen representativa de la catástrofe.
La fecha de la catástrofe, superpuesta sobre la imagen usando la propiedad position de CSS.
Un título breve con el nombre de la catástrofe.
Un enlace que lleve a la página de detalles de la catástrofe (por ejemplo, a dana-valencia-2024.html).
3. Diseño Responsive: La página debe estar optimizada para dispositivos móviles y ajustarse bien a pantallas de escritorio mediante el uso de media queries.

## Parte 2: Página de Catástrofe (Ejemplo: dana-valencia-2024.html)

`Secciones Obligatorias`
La página de detalles de la catástrofe debe incluir las siguientes secciones:

1. Encabezado:
Un título con el nombre de la catástrofe.
Un menú de navegación interno que enlace a cada sección de la página.
El menú debe ser sticky o static para facilitar la navegación durante toda la experiencia del usuario
2. Resumen de la catastrofe:
Una breve descripción de los efectos y daños causados por la catástrofe.
3. Mapa de Ubicación:
Insertar un mapa de la zona afectada usando un iframe de Google Maps o otra web similar. Puedes obtener el iframe desde maps.ie.
4. Centros de asistencia:
Lista de centros donde se ofrece asistencia, con detalles como la ubicación, capacidad y necesidades actuales.
5. Voluntariado (Emergencia activa):
Formulario simple para que los usuarios interesados en colaborar puedan inscribirse.
Secciones Opcionales
Elige al menos dos de las siguientes secciones para incluir en la página. Puedes adaptarlas a la catástrofe elegida o crear tus propios detalles.

Galería de imágenes: Muestra imágenes de la catástrofe y sus efectos. Utiliza una disposición flexbox para organizarlas.

Historia y contexto: Una breve sección que explique la causa de la catástrofe y antecedentes importantes.

Donaciones y Ayuda (Emergencia activa): Información sobre cómo se pueden realizar donaciones monetarias o materiales, resaltando los elementos que son más necesarios en este momento.

Notificaciones de Emergencia (Emergencia activa): Mensajes que resalten información de urgencia, con fecha y hora.

Contacto de Emergencias (Emergencia activa): Información de contacto de emergencia (números de teléfono, correos, etc.) de autoridades locales y organizaciones.
Impacto en la comunidad: Estadísticas de los efectos en la población y la infraestructura.

Actualización en Tiempo Real  (Emergencia activa): Un espacio para incluir enlaces a redes sociales o noticias recientes relacionadas con la catástrofe para ver actualizaciones en tiempo real.

Preguntas Frecuentes (FAQ): Una lista de preguntas y respuestas sobre cómo la gente puede ayudar o sobre los próximos pasos en la recuperación.


`Instrucciones de Diseño y Estilo:`

Responsive:  
Comienza el diseño pensando en dispositivos móviles y luego usa media queries para hacer ajustes en pantallas más grandes.
Organiza las tarjetas de catástrofes en una columna en móvil y en dos o tres columnas en vista de escritorio.
Posicionamiento:
Recuerda el uso de position para la imagen de cada tarjeta y para incluir el contenido, superpuesto dentro de la imagen.
Flexbox:
Utiliza flexbox para centrar el contenido y organizar las secciones, asegurándote de que el diseño se mantenga limpio y legible.
Metodología BEM:
Utiliza nombres de clases según la metodología BEM para facilitar la lectura y el mantenimiento del código. Se debe utilizar un único archivo "styles.css" tanto para la landingPage como para la página de cada catastrofe.