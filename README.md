# Audi Q5 2018 2.0L T Dynamic DSG — Página de Venta

Landing page de una sola página (single-page) para la venta de un Audi Q5 2018 Dynamic negro. Optimizada para móvil y desktop.

## Estado del proyecto

**En progreso.** El contenido y la estructura están completos. Solo faltan las **fotos reales** del coche para reemplazar los placeholders.

## Estructura de carpetas

```
audi-2018-venta/
├── index.html              # Página principal (todo en un archivo)
├── assets/
│   ├── images/             # Fotos del coche (por agregar)
│   │   └── adeudos.jpg     # Captura de consulta de adeudos (guardar aquí)
│   ├── css/                # Estilos extra (futuro)
│   └── js/                 # Scripts extra (futuro)
├── docs/
│   └── superpowers/
│       └── specs/          # Especificaciones de diseño
├── README.md               # Este archivo
└── TODO.md                 # Lista de pendientes
```

## Cómo usar

1. Abre `index.html` directamente en tu navegador (doble clic).
2. No requiere servidor ni instalación de dependencias.
3. Para publicar en internet, sube la carpeta completa a Netlify, Vercel, GitHub Pages, o cualquier hosting estático.

## Datos ya configurados

| Campo | Valor |
|-------|-------|
| Marca / Modelo | Audi Q5 2018 2.0L T Dynamic DSG |
| Color | Negra |
| Kilometraje | 70,000 km |
| Transmisión | DSG |
| Motor | 2.0L T (4 cilindros) |
| Capacidad | 5 pasajeros |
| Puertas | 5 |
| Combustible | Gasolina |
| Uso | Particular |
| Dueños | Único dueño |
| Tarjeta de circulación | Expedida marzo 2019 |
| Documentación | Todo pagado y verificado |
| Precio | **$360,000 MXN** (negociable, se consideran cambios) |
| Motivo de venta | Salida del país |
| Historial | Sin accidentes, sin problemas mecánicos |
| Verificaciones | Mayo 2020, 2022, 2024 (placa termina en 3) |
| Teléfono | [55 3677 7602](https://wa.me/525536777602) |
| Correo | juanandrese09@gmail.com |
| Ubicación | Bosques de las Lomas, CDMX |
| Calendario | [Agendar cita](https://calendar.app.google/anDiEw6q833T6PyH7) |

## Extras incluidos en el precio

- Pantalla Android 12.3" (Android 14, Snapdragon 665, 8GB RAM, 128GB ROM, 4G LTE, CarPlay & Android Auto) — valor +$50,000 MXN
- Cámara de reversa integrada (actualizable a 360°)
- Llanta de refacción completa
- Forros de cinturón de alcántara premium

## Pendientes (antes de publicar)

- [ ] **Fotos reales** — Reemplazar todos los URLs de `placehold.co` en la galería (8 fotos) y el hero (1 foto) por fotos propias guardadas en `assets/images/`
- [ ] **Comprobante de adeudos** — Guardar la captura de pantalla como `assets/images/adeudos.jpg`
- [ ] **Comprimir y optimizar las fotos** antes de subirlas (WebP recomendado)

## Mejoras implementadas recientemente

- [x] **Tipografía premium** — Playfair Display para headings + Inter para body
- [x] **Glassmorphism** — Cards con `backdrop-filter: blur()` para efecto cristal
- [x] **Optimización móvil** — Mobile-first, tipografía responsive, touch targets 44px+
- [x] **WhatsApp FAB** — Botón flotante de WhatsApp visible solo en móvil
- [x] **Touch swipe en lightbox** — Navegación por deslizamiento en la galería
- [x] **Lazy loading** — Carga diferida de imágenes de la galería
- [x] **Z-index scale** — Escala organizada (10, 30, 40, 50, 60)
- [x] **Focus states mejorados** — Outline rojo visible para navegación por teclado
- [x] **Animaciones fluidas** — Transiciones con easing `cubic-bezier(0.4, 0, 0.2, 1)`
- [x] **Timeline completo** — Fechas de verificaciones, mantenimiento y servicios
- [x] **Comprobante de adeudos** — Sección con captura de consulta oficial
- [x] **Tagline y badges** — "Lujo alemán, confianza total" + trato directo

## Tecnologías

- HTML5 semántico
- Tailwind CSS (via CDN)
- JavaScript vanilla (ES6+)
- Google Fonts (Playfair Display + Inter)

## Diseño

- **Estilo:** Dark mode premium, automotriz de lujo
- **Paleta:** Slate (grises oscuros) + Rojo (#DC2626) como acento
- **Tipografía:** Playfair Display (serif elegante) + Inter (sans-serif legible)
- **Efectos:** Glassmorphism, scroll reveal, lightbox con swipe táctil
- **Responsive:** Mobile-first con breakpoints sm/md/lg
- **Accesibilidad:** Focus states visibles, touch targets 44px+, `prefers-reduced-motion`

## Checklist pre-publicación

- [ ] Reemplazar `placehold.co` por fotos reales en hero + galería (8 fotos)
- [ ] Guardar `adeudos.jpg` en `assets/images/`
- [ ] Probar en móvil (iPhone SE, iPhone 14 Pro)
- [ ] Probar en desktop (Chrome, Safari, Firefox)
- [ ] Verificar que todos los enlaces funcionan (WhatsApp, email, calendario)
- [ ] Optimizar tamaño de las fotos (comprimir a <200KB cada una)
- [ ] Subir a Netlify / Vercel / GitHub Pages
