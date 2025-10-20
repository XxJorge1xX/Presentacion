# Presentación

Repositorio con una presentación web diseñada para mostrar proyectos, ideas y demostraciones técnicas de forma visual y accesible. La estructura del sitio está pensada para resaltar contenidos clave (proyectos, capturas, descripciones y demos) de forma clara y profesional.

Contiene archivos HTML, CSS y JavaScript, junto con recursos multimedia que puedes personalizar y desplegar fácilmente. Ideal para compartir tu portafolio, explicar conceptos con ejemplos interactivos o mostrar demos técnicas.

## Navbar (barra de navegación)

La página incluye un navbar moderno y funcional que facilita la navegación por la presentación. Características principales:

- Diseño responsivo: se adapta automáticamente a pantallas de escritorio, tablet y móvil. En dispositivos pequeños el navbar se colapsa en un botón tipo "hamburguesa".
- Sticky / fija: el navbar se mantiene visible en la parte superior mientras el usuario hace scroll, permitiendo un acceso rápido a las secciones principales.
- Enlaces con scroll suave: al hacer clic en un enlace del navbar, la página hace un desplazamiento suave hasta la sección correspondiente, mejorando la experiencia de lectura.
- Indicador de sección activa: el enlace correspondiente a la sección visible se resalta (clase activa), para que el usuario siempre sepa dónde se encuentra dentro de la presentación.
- CTA y elementos destacados: incluye un botón de llamada a la acción (por ejemplo, "Contacto" o "Ver demo") que puede destacarse con color o borde.
- Accesibilidad: marcado ARIA básico, foco visible y soporte para navegación por teclado para mejorar la usabilidad a usuarios con discapacidades.
- Personalización sencilla: colores, tipografías y orden de enlaces se controlan desde el archivo CSS y el HTML del encabezado; el comportamiento (por ejemplo, el colapso móvil o el scroll suave) se puede ajustar desde el script JS correspondiente.
- Soporte para iconos y logos: espacio para logo a la izquierda y opción de añadir iconos a los enlaces para mayor claridad visual.
- Opcional: toggle de modo oscuro/claro (se puede añadir fácilmente) y menús desplegables para secciones con subítems.

### Dónde modificarlo
- HTML: edita la estructura del navbar en index.html (o el archivo header.html si la plantilla está fragmentada).
- CSS: personaliza colores, espaciado y tipografías en css/navbar.css o en el archivo principal de estilos.
- JS: ajusta el comportamiento (colapso, scroll suave, activación de clases) en js/navbar.js o en el script principal.

### Recomendaciones rápidas
- Mantén los enlaces del navbar claros y concisos (Inicio, Proyectos, Sobre mí, Contacto).
- Usa un CTA visible para dirigir a la acción principal (ver demo, descargar CV, contactar).
- Verifica la accesibilidad con teclado y lector de pantalla tras cualquier cambio.
