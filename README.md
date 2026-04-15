# SOS Computación — Demo Rediseño

Demo visual del rediseño del sitio, inspirado en MercadoLibre y AXA.
**Solo frontend** — HTML/CSS/JS puro. Sin build, sin backend.

## Cómo mostrarle al cliente

**Opción 1 — rápido (doble click):**
- Abrir `index.html` en el navegador.
- Navegar a cualquier producto para ver la página de detalle.

**Opción 2 — servidor local (recomendado):**
```bash
cd sosdemo
python3 -m http.server 8000
# abrir http://localhost:8000
```

## Archivos

- `index.html` — Home estilo MercadoLibre (hero, categorías, grids, ofertas).
- `producto.html` — Ficha de producto estilo AXA/ML (galería, caja de compra, specs, relacionados).
- `styles.css` — Todo el diseño.
- `data/products.js` — 50 productos reales scrapeados del sitio actual.
- `captures/` — Screenshots del sitio viejo y el nuevo para comparar.

## Qué mejora vs el sitio actual

- Jerarquía visual clara (hero, secciones, cards pro)
- Tipografía moderna (Inter)
- Paleta amarillo/azul evolucionada, con espacios y contraste correctos
- Cards de producto estilo ML: descuento, precio tachado, cuotas, envío gratis
- Página de producto con caja de compra lateral, stock, envío estimado, CTAs claros
- Header sticky con búsqueda prominente
- Mobile-responsive
