# Rocalm — Tienda online de ropa de pilates y yoga

Proyecto Integrador de **Lenguajes de Marcas** (1.º DAM).
**Fita 1 (1.ª evaluación): prototipo estático** en HTML5 semántico y CSS3, responsive y sin JavaScript.

Rocalm es una marca ficticia de ropa técnica de pilates y yoga, de cortes finos y estilo minimalista. Todos los productos, precios, reseñas y datos de contacto son inventados.

## Cómo abrirlo

1. Descomprime el zip (no lo abras desde dentro del zip).
2. Abre `index.html` con el navegador. No hace falta servidor ni conexión a internet.

Recomendado: Chrome, Edge o Firefox actualizados. El filtro del catálogo usa el selector `:has()`, disponible en todos los navegadores modernos.

## Páginas

| Página | Contenido |
|---|---|
| `index.html` | Portada, ventajas, categorías, más vendidos, historia, tejidos, opiniones y boletín |
| `catalogo.html` | 8 productos con filtro por categoría y por actividad |
| 8 fichas de producto (`legging-alinea.html`, …) | Galería, color, talla, corte, tejido, cuidados, guía de tallas y reseñas |
| `carrito.html` | Cesta con resumen del pedido |
| `login.html` | Iniciar sesión y crear cuenta |
| `contacto.html` | Preguntas frecuentes, formulario y dirección |

## Estructura de carpetas

```
rocalm/
├── index.html, catalogo.html, carrito.html, login.html, contacto.html
├── 8 fichas de producto (*.html)
├── css/estilos.css      Hoja de estilos única, comentada y numerada por secciones
├── datos/catalogo.xml   Catálogo de productos en XML bien formado (Sprint 1)
├── fonts/               Fuente Inter en .woff2 (licencia SIL OFL)
├── img/                 Logotipo, imágenes de producto y de portada (SVG)
├── capturas/            Capturas en móvil, tableta y escritorio + validación W3C
├── backlog.md           Product Backlog, mapa del sitio y registro de sprint
├── FOTOS.md             Lista de fotos reales que sustituirán a las ilustraciones
```

## Contenidos del temario UD02 y dónde están

| Contenido | Dónde |
|---|---|
| Etiquetas semánticas (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `figure`, `address`) | Todas las páginas |
| Jerarquía de encabezados h1-h3 y textos `alt` | Todas las páginas |
| Tablas con `caption`, `thead`, `th scope` | Guía de tallas y cesta |
| Formularios: `fieldset`, `legend`, `label`, `select`, `textarea`, `email`, `password`, `number`, `required`, `datalist` | Contacto, login, fichas, buscador |
| `details` / `summary` | Fichas y contacto |
| Variables CSS (propiedades personalizadas) | `estilos.css`, sección 1 |
| `@font-face` | Sección 0 |
| Modelo de caja y `box-sizing` | Sección 2 |
| `position` (`absolute`, `relative`, `sticky`) y `float` | Tarjetas, cabecera, cesta |
| Flexbox | Cabecera, menú, portada, ventajas, historia |
| CSS Grid | Rejillas de productos, categorías, galería, reseñas |
| `grid-template-areas` | Pie de página, sección de tejidos y cesta |
| Media queries, *mobile first* (600 px y 960 px) | Secciones 16 y 17 |
| `border-radius`, `box-shadow`, `text-shadow`, degradados, `hsla`, `opacity`, `outline`, `border-image` | Tarjetas, portada, buscador, títulos |
| Selectores CSS3 (`:nth-child`, `:checked`, `:not`, `:has`, `::before`, atributos) | Galería, filtros, migas de pan |
| Transformaciones, transiciones y `@keyframes` | Tarjetas, categorías, logo, portada |
| Accesibilidad: enlace "saltar al contenido", foco visible, `aria-label`, `aria-current`, `prefers-reduced-motion` | Todas las páginas |

## Interactividad sin JavaScript

- **Filtro del catálogo:** botones de radio ocultos y el selector `:has()` (secciones 15l y 15m2 del CSS).
- **Galería de fotos:** cada miniatura es un `label` que marca un radio; el CSS muestra la foto marcada (sección 15k).
- **Color y talla:** radios con estilo de botón (sección 15k2).
- **Desplegables:** `details` y `summary`, nativos de HTML.

## Qué es de muestra (llega con JavaScript en la Fita 2)

- El **buscador** sugiere productos y actividades, pero al enviar lleva al catálogo completo.
- La **cesta** siempre muestra los mismos dos productos de ejemplo.
- **Inicio de sesión, boletín y contacto** no envían datos.
- Al elegir un color no cambia la foto.

## Validación

HTML y CSS validados con Nu Html Checker, el mismo motor que [validator.w3.org](https://validator.w3.org/): **0 errores**. Resultado en `capturas/validacion-w3c.txt`.

Probado a 375 px (móvil), 768 px (tableta) y 1280 px (escritorio) sin desbordamientos. Capturas en `capturas/`.

## Créditos

- Fuente **Inter**, de The Inter Project Authors, con licencia SIL Open Font License 1.1 (`fonts/LICENSE-Inter.txt`).
- Logotipo e ilustraciones de producto (4 vistas por prenda: frente, espalda y dos detalles): creación propia en SVG, con degradados, textura de tejido y costuras dibujadas.
- Desarrollado con ayuda de un asistente de IA (Claude) para generar y revisar código. Las decisiones de diseño, la temática y la validación con usuarios son del alumno.
