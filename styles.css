# 24 Street Web V0

Prototipo móvil-first para el QR del porta menú.

## Objetivo de esta versión

- Un QR específico por sucursal.
- Acceso inmediato a menú digital, Google Maps, Instagram y eventos.
- Base visual oscura, urbana e hipnótica, sin depender todavía de fotografías de producto.
- Código simple: HTML, CSS y JavaScript puro.

## Probar localmente

Abrí `index.html` en el navegador o ejecutá un servidor local:

```bash
python -m http.server 8080
```

Luego visitá:

- `http://localhost:8080/?s=S25`
- `http://localhost:8080/?s=AB`
- `http://localhost:8080/?s=CE`
- `http://localhost:8080/?s=FL`

## Arquitectura recomendada para producción

```text
/
/menu
/eventos
/eventos/:slug
/sucursales/:codigo
/promos/:slug
/go/:codigo
```

El QR del porta menú debe apuntar a una URL propia y permanente, por ejemplo:

```text
https://bar24street.com/go/S25
```

Esa ruta puede redirigir a:

```text
https://bar24street.com/?s=S25&utm_source=qr&utm_medium=portamenu&utm_campaign=acceso_digital&utm_content=S25
```

## Pendientes antes de publicar

1. Confirmar Instagram, dirección, horarios y estado de cada sucursal.
2. Cargar menú y precios vigentes.
3. Reemplazar los bloques tipográficos por fotos reales de producto.
4. Crear páginas reales de menú y eventos.
5. Instalar GA4 y medir `menu_click`, `maps_click`, `instagram_click` y `event_click`.
6. Optimizar imágenes en WebP/AVIF.
7. Publicar en GitHub Pages para prueba y luego en Hostinger.

## Repositorio recomendado

`Parisluis/24street-web`

No se modificó ningún repositorio existente.
