# Diseño: Plantilla Web Venta de Coche Usado

## Fecha
2025-01-24

## Resumen
Single-page HTML template para anunciar la venta de un coche usado. Estilo moderno, profesional, con placeholders claros para facilitar el reemplazo de contenido.

## Estructura de Secciones
1. **Hero** — Imagen principal, título del anuncio, precio destacado, CTA "Agendar cita"
2. **Specs Rápidas** — Grid 4-6 tarjetas con datos clave (año, km, transmisión, combustible, motor, color)
3. **Galería** — Grid responsive de thumbnails, lightbox básico con JS vanilla. Placeholders numerados (img-1 a img-8)
4. **Descripción** — Texto libre para estado, extras, motivo de venta
5. **Historial Documentación** — Timeline vertical por categorías: Documentos legales | Verificaciones | Mantenimiento. Cada ítem: fecha + descripción
6. **Agendar Cita** — Formulario: nombre, teléfono, email, fecha preferida, mensaje. Sin backend, solo UI lista para conectar
7. **Footer** — Contacto del vendedor

## Estilo Visual
- Paleta: fondo slate-900, tarjetas slate-800, acento emerald-500 para CTAs
- Tipografía: Inter (Google Fonts)
- Bordes redondeados lg, sombras sutiles, espaciado generoso (py-16 entre secciones)
- Totalmente responsive (mobile-first)

## Tecnología
- HTML5 semántico
- Tailwind CSS v4 via CDN
- JavaScript vanilla (galería + formulario)
- Sin dependencias de build

## Placeholders
- Imágenes: `https://placehold.co/800x600/1e293b/475569?text=Foto+[N]`
- Textos: marcados con comentarios `<!-- REEMPLAZAR: ... -->`
- Datos: valores de ejemplo con formato realista

## Entregable
Un único archivo `index.html` listo para abrir en navegador.
