# TODO — Audi Q5 2018 Venta

## Estado actual

**Mayoría completado.** Solo faltan las **fotos reales** y guardar el comprobante de adeudos.

---

## Críticos (antes de publicar)

- [ ] **Fotos reales** — Reemplazar todos los URLs de `placehold.co` en la galería y el hero por fotos propias.
  - Hero: línea ~50 — `assets/images/hero.jpg`
  - Galería: 8 fotos — `assets/images/foto-1.jpg` a `foto-8.jpg`
- [ ] **Comprobante de adeudos** — Guardar la captura como `assets/images/adeudos.jpg`
- [ ] **Optimizar fotos** — Comprimir cada foto a <200KB (WebP recomendado)

## Datos completados ✅

- [x] **Precio** — $330,000 MXN
- [x] **Motor** — 2.0L T (4 cilindros, confirmado con tarjeta)
- [x] **Transmisión** — DSG
- [x] **Modelo exacto** — Audi Q5 2018 2.0L T Dynamic DSG (5 puertas)
- [x] **Capacidad** — 5 pasajeros (confirmado con tarjeta)
- [x] **Uso** — Particular (confirmado con tarjeta)
- [x] **Precio no negociable** — No considero cambios
- [x] **Verificaciones** — Mayo 2020, 2022, 2024 (placa termina en 3)
- [x] **Tenencias** — Todas pagadas al corriente
- [x] **Tarjeta de circulación** — Expedida marzo 2019
- [x] **Historial limpio** — Sin accidentes, sin problemas mecánicos
- [x] **Servicios** — 60,000 km en agencia (Dic 2023), cambio de llantas (Mar 2025)
- [x] **Revisión mecánica** — Agosto 2024 en taller certificado
- [x] **Pantalla Android** — Especificaciones exactas agregadas (12.3" Android 14, SD665, 8GB/128GB, 4G LTE)
- [x] **Cámara de reversa** — Con opción de actualizar a 360°
- [x] **Llanta de refacción** — Agregada como característica
- [x] **Forros de cinturón de alcántara** — Agregada como característica
- [x] **Tagline** — "Lujo alemán, confianza total..."
- [x] **Trato directo / Sin intermediarios** — Badges en hero

## Mejoras UX/UI implementadas ✅

- [x] **Tipografía premium** — Playfair Display (headings) + Inter (body)
- [x] **Glassmorphism** — Cards con `backdrop-filter: blur(16px)`
- [x] **Mobile-first responsive** — Tipografía, padding, gap adaptativos
- [x] **Touch targets 44px+** — Todos los botones y enlaces accesibles
- [x] **WhatsApp FAB flotante** — Visible solo en móvil, sticky bottom-right
- [x] **Touch swipe en lightbox** — Navegar galería con deslizamiento
- [x] **Lazy loading** — `loading="lazy"` en todas las imágenes de la galería
- [x] **Z-index scale** — 10 (glass), 30 (sticky), 40 (dropdown), 50 (modal), 60 (toast)
- [x] **Focus states mejorados** — Outline rojo `#DC2626` con offset 3px
- [x] **Animaciones fluidas** — `cubic-bezier(0.4, 0, 0.2, 1)` a 500ms
- [x] **Scroll reveal optimizado** — `rootMargin: 0px 0px -40px 0px`, threshold 0.08
- [x] **Comprobante de adeudos** — Sección en timeline con captura
- [x] **Swipe hint** — Indicador "Desliza para navegar" en lightbox móvil

## Mejoras futuras (opcional)

- [ ] **Mapa embebido** — Google Maps con ubicación exacta en Bosques de las Lomas
- [ ] **Schema.org JSON-LD** — Rich snippets en Google (Product, Offer, Vehicle)
- [ ] **Meta tags SEO** — Open Graph, Twitter Cards, descripción, keywords
- [ ] **PWA** — Manifest.json + service worker para instalar como app
- [ ] **Analytics** — Google Analytics o Plausible para tracking de visitas
- [ ] **Formulario de contacto** — Netlify Forms o Formspree como alternativa al calendario
- [ ] **Galería con zoom** — Pinch-to-zoom en lightbox para ver detalles del coche

## Cómo buscar placeholders restantes

Abre `index.html` en cualquier editor y busca:
- `placehold.co` — imágenes de prueba (9 en total: 1 hero + 8 galería)
