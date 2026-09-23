# miRenar — Portal rediseñado (prototipo)

Rediseño completo del frontend de mi.renar.gob.ar como prototipo navegable, construido con Design Components (HTML) sobre el design system **Industry** (wireframe azul acero, Barlow Condensed/Barlow, tarjetas "blueprint" con marcas de registro).

Todos los datos (personas, armas, credenciales, pagos, aranceles, etc.) son **mock**, sin información real.

## Cómo verlo
Abrí `Home.dc.html` en el navegador. Desde ahí se navega a todas las secciones y se puede volver al inicio.

## Estructura
- `Header.dc.html`, `Footer.dc.html` — navegación y pie de página compartidos, importados por todas las páginas.
- `Home.dc.html` — inicio: hero, acceso miArgentina, accesos rápidos.
- `Tramites.dc.html`, `Credenciales.dc.html`, `Municiones.dc.html`, `Personas.dc.html`, `Armas.dc.html`, `Comercios.dc.html`, `Profesionales.dc.html` — secciones principales de gestión.
- `Nomenclador.dc.html`, `Aranceles.dc.html`, `Vuce.dc.html`, `Destruccion.dc.html`, `PuntosFronterizos.dc.html` — recursos y consultas.
- `Pagos.dc.html`, `EstadoSistema.dc.html`, `DomicilioElectronico.dc.html`, `Taller.dc.html` — cuenta y servicios.
- `Ayuda.dc.html`, `Encuesta.dc.html`, `Perfil.dc.html` — soporte y cuenta de usuario.
- `_ds/` — bundle del design system Industry (estilos y componentes).
- `support.js` — runtime de los Design Components.

## Funcionalidad
Búsqueda global, filtros de tablas, menús desplegables, modales de detalle, badges de estado y formulario de encuesta funcionan con lógica e interacción real sobre datos mock — listos para conectarse a una API real en el futuro.
