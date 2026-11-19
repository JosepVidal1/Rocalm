# Rocalm — Product Backlog (Sprint 1)

**Temática:** tienda online de ropa de pilates y yoga, de acabados y cortes finos, estilo minimalista.

## Product Backlog (ordenado por prioridad)

| # | Historia de usuario | Fita |
|---|---|---|
| 1 | Como visitante, quiero ver una página de inicio con la marca y los productos destacados, para saber qué vende la tienda. | 1 |
| 2 | Como visitante, quiero un menú de navegación en todas las páginas, para moverme por la web. | 1 |
| 3 | Como cliente, quiero ver el catálogo con foto, nombre y precio de cada prenda, para comparar productos. | 1 |
| 4 | Como cliente, quiero ver el detalle de un producto (descripción, tallas, color, guía de tallas), para decidir si lo compro. | 1 |
| 5 | Como cliente, quiero un formulario de contacto, para hacer preguntas a la tienda. | 1 |
| 6 | Como cliente, quiero que la web se vea bien en móvil, tableta y ordenador, para comprar desde cualquier dispositivo. | 1 |
| 7 | Como cliente, quiero filtrar el catálogo por categoría y actividad, para encontrar antes lo que busco. | 2 |
| 8 | Como cliente, quiero añadir productos a un carrito y ver el total, para preparar mi compra. | 2 |
| 9 | Como cliente, quiero que el formulario me avise si me equivoco al rellenarlo, para no enviar datos incorrectos. | 2 |
| 10 | Como administrador, quiero que el catálogo se cargue desde un fichero JSON, para cambiar productos sin tocar el HTML. | 2 |
| 11 | Como administrador, quiero que los datos del catálogo se validen con un esquema, para evitar errores. | 3 |
| 12 | Como administrador, quiero guardar y consultar los pedidos, para gestionar las ventas. | 3 |

## Mapa del sitio

```
index.html (Inicio)
├── catalogo.html (Catálogo con filtro por categoría)
│   └── 8 fichas de producto: legging-alinea.html, legging-flow.html, top-linea.html,
│       camiseta-brisa.html, body-contorno.html, chaqueta-define.html,
│       sudadera-calma.html, calcetines-grip.html
├── carrito.html (Cesta)
├── login.html (Iniciar sesión y crear cuenta)
└── contacto.html (Preguntas frecuentes y formulario)
```

## Datos

- `datos/catalogo.xml`: catálogo de ejemplo con 8 productos (XML bien formado).

## Registro de sprint

| Fecha | Qué he hecho | Qué me bloquea | Próximo paso |
|---|---|---|---|
| 15/11/2026 | Elegida la temática (tienda de ropa de pilates y yoga). Backlog de 12 historias, mapa del sitio y `catalogo.xml` con 8 productos. Esqueleto HTML de 4 páginas sin CSS. | Nada | Hoja de estilos |
| 15/11/2026 | Nombre de marca: Rocalm. Hoja de estilos *mobile first* con Flexbox, Grid y media queries. | No tengo fotos reales | Mejorar portada y ficha |
| 15/11/2026 | Portada con categorías, opiniones y boletín. Ficha con galería y desplegables. | Fotos y vídeos reales | Interactividad con CSS |
| 15/11/2026 | Filtro del catálogo y galería sin JavaScript (`:has()` y radios). 8 fichas de producto y cesta. | La cesta real necesita JavaScript | Paleta más clara y logotipo |
| 16/11/2026 | Paleta clara, logotipo, buscador con `datalist`, login, filtro por actividad. Corte, tejido, cuidados y reseñas en cada ficha. | El buscador no busca de verdad sin JavaScript | Revisar el temario de la Q4 |
| 19/11/2026 | Añadidos `grid-template-areas`, `@font-face`, `box-shadow`, `text-shadow`, `hsla` y `border-image`. Quitados los vídeos vacíos. Validación W3C con 0 errores. README, capturas y repositorio Git. | Fotos reales pendientes | Fotos y ensayar la demo |

## Retrospectiva de la Fita 1 (escríbela tú)

Dos o tres líneas con tus palabras. Es tu reflexión personal, así que no la he rellenado.

- **Qué me ha costado más:**
- **Qué ha funcionado bien:**
- **Qué haré distinto en la Fita 2:**
