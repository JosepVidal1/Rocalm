# Rocalm — Fotos reales pendientes

Ahora la web usa ilustraciones SVG. Cada foto real se guarda con el mismo nombre (cambiando `.svg` por `.jpg`) y se actualiza la ruta en el HTML.

## Reglas para que todas parezcan de la misma marca

- Fondo liso, crema o gris muy claro. Luz suave y natural.
- Colores de ropa del catálogo: negro, arena, verde salvia, gris piedra, blanco roto.
- Producto en vertical (4:5, por ejemplo 1200 × 1500 px). Portada en horizontal (4:3).
- Menos de 300 KB por foto, en JPG o WebP.

## Lista

| Archivo | Dónde se ve | Qué debe mostrar |
|---|---|---|
| `img/portada.jpg` | Fondo de la portada | Mujer en clase de pilates reformer, estudio luminoso |
| `img/cat-leggings.jpg` … `cat-accesorios.jpg` | Compra por categoría | Una foto por categoría |
| `img/p01.jpg` … `img/p08.jpg` | Catálogo y fichas | Foto principal de cada producto (nombres en `datos/catalogo.xml`) |
| `img/p01-2.jpg` … `img/p08-2.jpg` | Al pasar el ratón y galería | Vista trasera |
| `img/p01-3.jpg`, `-4.jpg` (y así hasta `p08`) | Galería de la ficha | Detalle de la parte superior e inferior |
| `img/historia.jpg` | Nuestra historia | Primer plano de tejido y costura plana |

## De dónde sacarlas

1. **Bancos gratuitos** (válidos para un proyecto de clase): Pexels, Unsplash, Pixabay. Busca "pilates reformer", "yoga leggings", "activewear studio".
2. **Generadas con IA:** Google Flow, Ideogram, Midjourney.

Indicación para IA (cambia solo la prenda y el color en cada foto):

> Studio product photo of a woman wearing high-waisted black seamless leggings, front view, plain cream background, soft natural light, minimalist activewear catalog, 4:5 vertical
