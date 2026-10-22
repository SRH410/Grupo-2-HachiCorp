# AmiPet - TB3 (Sprint 1)

## Estructura

- `landing-page/html/`: Landing Page y paginas publicas.
- `landing-page/css/styles.css`: hoja de estilos del Landing Page.
- `web-application/html/`: catalogo y flujos de la aplicacion web.
- `web-application/css/styles.css`: hoja de estilos de la aplicacion web.
- `assets/images/`: ilustraciones locales de respaldo para las fotografias.

No se incluye JavaScript porque el alcance de TB3 corresponde a HTML y CSS. JavaScript, consumo de APIs y la integracion de IA pertenecen al Sprint 2 / TB4.

## Abrir en Visual Studio Code

1. Descomprime el archivo ZIP.
2. Abre la carpeta `AmiPet_TB3` en Visual Studio Code.
3. Instala o habilita la extension Live Server si aun no la tienes.
4. Abre `landing-page/html/index.html` y selecciona **Open with Live Server**.
5. Para revisar la aplicacion web, abre `web-application/html/index.html` con Live Server.

## Alcance y limitaciones de TB3

- Los enlaces entre pantallas son navegables.
- Los formularios usan validacion nativa del navegador (`required`, `type`, `pattern`, `minlength`, `maxlength`).
- No hay autenticacion real, base de datos, guardado de formularios, filtrado dinamico ni conexion a IA.
- Las fotografias principales intentan cargar imagenes de Unsplash. Si no hay conexion, cada bloque tiene una ilustracion SVG local de respaldo.
- Las pantallas principales incluyen `lang="es-419"` y hay versiones de entrada en ingles con `lang="en-US"`.
- Se usan landmarks semanticos y atributos ARIA para navegacion, formularios y mensajes.
- Los comentarios de codigo se omitieron; por tanto, no hay comentarios con tildes.

## Comprobacion visual

Compara las pantallas con el archivo Figma `AmiPet - Diseño TB2`, pagina `02 - Design System + Mockups`. La paleta principal es `#A88AED`, con estados `#66BB6A` y `#EF5350`, fondos claros y bordes suaves. Las tipografias son Outfit para encabezados y Figtree para texto.
