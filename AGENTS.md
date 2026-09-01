# AGENTS.md — Proyecto: Rediseño Web CONBUD

## Qué es este proyecto
Rediseño del sitio web de CONBUD, una dispensaria de cannabis legal en Nueva York
con tres tiendas (Lower East Side, Mott Haven y Yankee Stadium). El objetivo es
construir una landing page (`index.html`) que mejore la conversión de visitantes
a clientes, corrigiendo los problemas de la web actual (conbud.com).

## Stack técnico
- HTML5 + CSS3 puro (sin frameworks de build, sin React/Vue).
- JavaScript vanilla solo si es estrictamente necesario (ej. acordeón de FAQ,
  carrusel de productos, modal de verificación de edad).
- Todo el código debe vivir en un único archivo `index.html` con `<style>` y
  `<script>` inline, salvo que se indique lo contrario.
- Responsive obligatorio: mobile-first, breakpoints para tablet y desktop.
- Sin dependencias externas de pago. Si se usan íconos, usar SVG inline o una
  librería CDN gratuita (ej. Lucide, Font Awesome free).

## Fuente de verdad para diseño
Lee siempre `DESIGN.md` antes de generar o modificar código visual. Contiene la
paleta de colores, tipografía, tono de marca y el orden exacto de las secciones.
Usa `screen.png` como referencia de estilo visual (composición, densidad,
sensación general), no la copies literalmente.

## Reglas de trabajo
1. No inventes información de producto, precios o promociones reales: usa
   placeholders claramente marcados (ej. "$45.00 — placeholder") donde no haya
   datos confirmados.
2. Respeta el orden de secciones definido en `DESIGN.md`. No agregues ni quites
   secciones sin señalarlo explícitamente en tu resumen de cambios.
3. Cada sección debe tener un único CTA principal claro. Evita repetir el mismo
   botón más de una vez por sección.
4. Todo el contenido de cara al usuario debe estar en español, salvo el nombre
   de marca "CONBUD" y términos de producto que se mantengan en inglés por uso
   común (ej. "pre-rolls").
5. Incluye siempre el aviso legal de consumo responsable y la verificación de
   edad 21+ — es un requisito legal, no opcional.
6. Antes de dar por terminada una tarea, genera una captura o descripción del
   resultado en el Artifact para que pueda revisarlo sin leer todo el diff.
7. Si vas a tomar una decisión de diseño no especificada en `DESIGN.md`,
   explícala brevemente en el resumen de la tarea en vez de decidir en silencio.

## Definición de "hecho"
- El HTML valida sin errores graves.
- La página se ve correctamente en mobile (375px), tablet (768px) y desktop (1440px).
- Todas las secciones de `DESIGN.md` están presentes en el orden indicado.
- Los CTAs son visualmente consistentes (mismo color, misma forma) en toda la página.
