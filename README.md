# Web Diputada 8

Sitio estático en HTML/CSS con Bootstrap para una campaña/página informativa.

## Estructura del proyecto
- `index.html`: página principal con secciones (hero, slider, noticias, propuestas, sobre mí, contacto).
- `style.css`: estilos personalizados y overrides de Bootstrap.
- `images/`: recursos gráficos (logos, banners, fotos).

## Cómo usar
1) Abrir `index.html` en el navegador.
2) Editar textos, enlaces e imágenes directamente en `index.html`.
3) Ajustar estilos en `style.css` si necesitas cambios de marca.

Si usas un servidor local opcional:
```bash
    python -m http.server 8000
```
Luego abre `http://localhost:8000` en el navegador.

## Edición rápida (recomendaciones)
- Navegación: los links del menú apuntan a IDs (`#inicio`, `#sobre-mi`, `#propuestas`, `#contacto`). Si cambias títulos o secciones, actualiza esos IDs.
- Imágenes: reemplaza los archivos en `images/` manteniendo los mismos nombres o actualiza las rutas en `index.html`.
- Noticias: actualiza el título, fecha y enlace de cada tarjeta. Mantén un formato de fecha consistente.
- Contacto: reemplaza los datos de ejemplo por información oficial.

## Personalización de estilos
- La paleta y tipografías se manejan en `style.css`.
- Bootstrap se carga por CDN; puedes cambiar versión si es necesario.

## Deploy (estático)
Puedes publicar con cualquier hosting estático (GitHub Pages, Netlify, Vercel, etc.) subiendo estos archivos tal cual.

## Checklist antes de publicar
- Reemplazar textos lorem/placeholder.
- Revisar imágenes (peso, nitidez, licencias).
- Verificar enlaces y redes sociales.
