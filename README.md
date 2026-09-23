# miRenar — Portal rediseñado (prototipo)

Rediseño completo del frontend de mi.renar.gob.ar como prototipo navegable, construido con Design Components (HTML) sobre el design system **Industry** (wireframe azul acero, Barlow Condensed/Barlow, tarjetas "blueprint" con marcas de registro).

Todos los datos (personas, armas, credenciales, pagos, aranceles, etc.) son **mock**, sin información real.

## Cómo verlo
Abrí `index.html` en el navegador (redirige a `pages/Home.dc.html`), o abrí directamente `pages/Home.dc.html`. Desde ahí se navega a todas las secciones y se puede volver al inicio.

## Estructura
- `index.html` — redirección a la home del prototipo, para poder abrir el proyecto desde la raíz.
- `pages/` — todas las páginas del prototipo (`.dc.html`), enlazadas entre sí por nombre de archivo:
  - `Header.dc.html`, `Footer.dc.html` — navegación y pie de página compartidos, importados por todas las páginas.
  - `Home.dc.html` — inicio: hero, acceso miArgentina, accesos rápidos.
  - `Tramites.dc.html`, `Credenciales.dc.html`, `Municiones.dc.html`, `Personas.dc.html`, `Armas.dc.html`, `Comercios.dc.html`, `Profesionales.dc.html` — secciones principales de gestión.
  - `Nomenclador.dc.html`, `Aranceles.dc.html`, `Vuce.dc.html`, `Destruccion.dc.html`, `PuntosFronterizos.dc.html` — recursos y consultas.
  - `Pagos.dc.html`, `EstadoSistema.dc.html`, `DomicilioElectronico.dc.html`, `Taller.dc.html` — cuenta y servicios.
  - `Ayuda.dc.html`, `Encuesta.dc.html`, `Perfil.dc.html` — soporte y cuenta de usuario.
- `assets/` — recursos compartidos:
  - `js/support.js` — runtime de los Design Components.
  - `design-system/industry/` — bundle del design system Industry (estilos y componentes).

## Funcionalidad
Búsqueda global, filtros de tablas, menús desplegables, modales de detalle, badges de estado y formulario de encuesta funcionan con lógica e interacción real sobre datos mock — listos para conectarse a una API real en el futuro.
