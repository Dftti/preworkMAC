# Plantastole — Contexto de Marca y Tienda

> Archivo maestro de referencia para la creación de contenido, estrategia y comunicaciones de Plantastole.
> Última actualización: Marzo 2026

---

## 1. Identidad de Marca

**Nombre:** Plantas Tole / Plantastole
**Slogan:** "Plantas que transforman espacios"
**Fundación:** Junio 2023
**Fundadores:** Felipe y Diego (amigos de la infancia)
**Plataforma e-commerce:** Shopify
**URL:** [plantastole.cl](https://plantastole.cl)

**Qué es Plantas Tole:**
Tienda boutique de plantas y diseño verde. E-commerce en Shopify + tienda física en Vitacura. No es un vivero masivo: es una selección curada de plantas para quienes entienden que un buen hogar también es verde.

**Historia:**
Felipe es vivero tercera generación, con experiencia familiar profunda en plantas ornamentales. Diego tiene background en diseño y marketing digital. Juntos crearon Plantastole para ofrecer plantas grandes, sanas y listas para decorar, eliminando el ensayo y error de elegir plantas para el hogar chileno.

**Propuesta de valor:**
- Plantas seleccionadas una a una (no es compra a granel)
- Despacho exclusivo con empaque cuidado
- Garantía de 14 días
- Atención personalizada pre y post venta
- Envío gratis en compras sobre $120.000 CLP

---

## 2. Identidad Visual — Colores

### Paleta Principal

| Color | HEX | RGB | Uso |
|---|---|---|---|
| Verde Tole (primario) | `#1B321B` | `27, 50, 27` | Fondos, headers, texto principal, nav, botón de texto |
| Dorado Tole (acento) | `#D3A150` | — | Botones, bordes de tip boxes en blogs, CTAs premium |
| Durazno suave | `#F6CFB2` | `246, 207, 178` | Fondos secundarios, cajas de tips, elementos suaves, CTA buttons |
| Crema | `#FAF7F4` | — | Fondos de cards, Judge.me reviews, backgrounds suaves |
| Blanco | `#FFFFFF` | `255, 255, 255` | Fondo principal, texto sobre verde |
| Gris Medio | `#BFBFBF` | `191, 191, 191` | Contraste de fondo, elementos secundarios |
| Amarillo Estrellas | `#F8E714` | `248, 231, 20` | Rating/reseñas (Judge.me) |

> **Nota:** `#D3A150` es el dorado que se usa en blogs y piezas de contenido (tip boxes, bordes, CTAs premium). `#F6CFB2` es el durazno del tema Shopify (botones del sitio). Son distintos.

### Variables CSS del Sitio (`:root` Shopify)

```css
--color-foreground: 27,50,27;             /* #1B321B */
--color-background: 255,255,255;          /* #FFFFFF */
--color-background-contrast: 191,191,191; /* #BFBFBF */
--color-button: 246,207,178;              /* #F6CFB2 */
--color-button-text: 27,50,27;            /* #1B321B */
--color-badge-border: 27,50,27;           /* #1B321B */
--color-badge-background: 255,255,255;    /* #FFFFFF */
--color-link: 255,255,255;                /* #FFFFFF */
--color-secondary-button: 255,255,255;    /* #FFFFFF */
--jdgm-primary-color: #1B321B;
--jdgm-star-color: #F8E714;
```

---

## 3. Identidad Visual — Tipografías

| Fuente | Uso | Estilo |
|---|---|---|
| **Playfair Display** | Headings, títulos de blog, H1–H3 | Serif elegante, transmite premium |
| **Lato** | Body text, párrafos, descripciones | Sans-serif limpia, legible |
| **Cormorant Garamond** | Alternativa a Playfair (Shopify) | Serif refinada |
| **Montserrat** | Alternativa a Lato (Shopify) | Sans-serif moderna |

### Variables CSS Tipografía

```css
--font-heading-family: "Playfair Display", serif;
--font-heading-weight: 400;
--font-heading-scale: 1.0;
--font-body-family: Lato, sans-serif;
--font-body-weight: 400;
--font-body-weight-bold: 700;
--font-body-scale: 1.0;
```

**Reglas:**
- Playfair Display (headings) + Lato (body) = combinación principal
- Cormorant Garamond + Montserrat = alternativa válida para Shopify
- Máximo 2 familias por pieza de comunicación

---

## 4. Template de Blog HTML (Shopify)

Especificaciones técnicas para blogs embebidos en Shopify:

- **Contenedor:** `max-width: 900px`
- **Sizing:** usar `px !important` (no rem/em — Shopify los sobreescribe)
- **Estructura:** Navbar → Hero con logo grande → Intro → Secciones numeradas (01—) → Tip boxes con borde izquierdo dorado → Product boxes verde → Footer CTA
- **Tip boxes:** borde izquierdo `#D3A150` (dorado), fondo `#FAF7F4` (crema)
- **Product boxes:** fondo `#1B321B` (verde)
- **Botones:** `border-radius: 30px`
- **Headings:** Playfair Display | **Body:** Lato
- **Logo URL:** `https://plantastole.cl/cdn/shop/files/LOGO_PLANTAS_TOLE_2.png?v=1718060662&width=160`

---

## 5. Diseño UI — Especificaciones Técnicas del Sitio

```css
/* Layout */
--page-width: 140rem; /* 2240px máx */
--header-height: 104px;

/* Bordes y radios */
--buttons-radius: 10px;
--buttons-shadow-opacity: 5px; /* blur */
--product-card-corner-radius: 2.0rem;
--collection-card-corner-radius: 2.2rem;
--inputs-radius: 0px;

/* Grid */
--grid-desktop-horizontal-spacing: 4px;
--grid-desktop-vertical-spacing: 4px;
--grid-mobile-horizontal-spacing: 2px;
--grid-mobile-vertical-spacing: 2px;

/* Animaciones */
--animation-fade-in: fadeIn .6s cubic-bezier(0, 0, .3, 1);
--animation-slide-in: slideIn .6s cubic-bezier(0, 0, .3, 1) forwards;
--duration-default: .2s;
--duration-long: 3s;
```

---

## 6. Tienda Física

**Dirección:** Tabancura 1610, Vitacura, Santiago, Chile

**Horario:**
- Martes a Viernes: 10:00 – 19:00
- Sábado: 10:00 – 16:30
- Domingo y Lunes: Cerrado

---

## 7. E-Commerce y Operación

### Contacto
- **Email:** contacto@plantastole.cl
- **WhatsApp/Teléfono:** +56 9 3697 6319
- **Instagram:** [@plantastole](https://www.instagram.com/plantastole/)
- **Facebook:** [Plantas Tole](https://www.facebook.com/profile.php?id=61560963639033)

### Envíos
- Despacho **solo Región Metropolitana (RM)**
- Envío gratis en compras sobre **$120.000 CLP**
- Tiempo de despacho: **1 a 4 días hábiles** (martes a viernes)
- Sistema de despacho propio

### Garantías y Devoluciones
- **14 días de garantía** en plantas
- **7 días** para productos dañados al llegar (reemplazo o solución)
- Cambios y devoluciones se evalúan caso a caso

### Reseñas
- Plataforma: **Judge.me**
- Rating promedio: **4.82 / 5.0** (49+ reseñas verificadas)
- Métodos de pago: estándar de Shopify Chile

---

## 8. Catálogo de Productos

### Categorías y URLs

| Categoría | URL |
|---|---|
| Plantas de Interior | `/collections/plantas-de-interior` |
| Terraza y Exterior | `/collections/terraza-y-exterior` |
| Únicas y Exclusivas | `/collections/formatos-unicos` |
| Para Principiantes ("mata plantas") | `/collections/para-principiantes` |
| Pet Friendly | `/collections/pet-friendly` |
| Maceteros | `/collections/macetero` |
| Cuidado de tus Plantas (Vitalimás) | `/collections/vitalimas` |
| Frutales | `/collections/frutales` |

**Subcategorías Exterior:**
- Pleno Sol / Semisol
- Semisombra
- Con Flor
- Frutales
- Helechos

### Productos Destacados (Precios marzo 2026, CLP)

**Interior:**
| Producto | Precio | Notas |
|---|---|---|
| Kentia | $28.090 (antes $32.990) | Oferta activa |
| Longifolio | $34.990 | — |
| Cordatum | Desde $24.990 | — |
| Manto de Eva XL | $219.990 (antes $299.990) | Formato nuevo, oferta |

**Exterior / Frutales:**
| Producto | Precio | Notas |
|---|---|---|
| Strelitzia Reginae | $99.990 (antes $109.990) | Oferta |
| Yuca | $149.990 | — |
| Naranjo Cara Cara (M) | $64.990 (antes $84.990) | Oferta, 5.0★ |
| Limequat | $87.990 (antes $109.990) | Oferta, 5.0★ |
| Kumquat | $84.990 (antes $109.990) | Oferta, 5.0★ (3 reseñas) |
| Mandarino (L) | $74.990 (antes $99.990) | Oferta, 5.0★ |

**Rango de precios:**
- Entrada: ~$24.990 (plantas interior medianas)
- Medio: $60.000 – $100.000 (frutales, plantas grandes)
- Premium: $150.000 – $300.000 (formatos XL, únicas y exclusivas)

---

## 9. Navegación del Sitio

```
Plantas
  ├── Interior
  └── Exterior
       ├── Pleno Sol / Semisol
       ├── Semisombra
       ├── Con Flor
       ├── Frutales
       └── Helechos
Maceteros
Cuidado de tus Plantas
Sobre Nosotros       → /pages/sobre-plantas-tole
Contacto             → /pages/contact
FAQ                  → /pages/preguntas-frecuentes
Blog                 → /blogs
```

---

## 10. Público Objetivo

### Perfil Principal (~65%)
- **Género:** Mujeres
- **Edad:** 30+ años
- **Segmento socioeconómico:** ABC1
- **Ubicación:** Santiago RM, comunas del sector oriente (alineado con Vitacura)

### Características Psicográficas
- Valoran la estética y el diseño en sus espacios
- Buscan calidad sobre cantidad
- Dispuestas a invertir en plantas como elemento decorativo y de bienestar
- Activas en Instagram como canal de descubrimiento
- Aprecian el servicio personalizado y la atención al detalle

### Segmentos Secundarios
- Parejas jóvenes decorando su primer departamento
- Familias con jardín buscando exterior/frutales
- Regaladores (plantas como gift premium)

---

## 11. Tono de Voz y Estilo de Comunicación

**Experto pero accesible, educativo sin ser técnico.**

- Hablamos con conocimiento pero sin jerga botánica innecesaria
- Tono cálido, cercano, nunca corporativo ni genérico
- Evitamos frases de marketing vacías ("la mejor calidad", "los mejores precios")
- Usamos un lenguaje que inspira y educa al mismo tiempo
- En WhatsApp: tono servicial y suave, no agresivo comercialmente
- En blogs: narrativo, con tips prácticos, sin tecnicismos
- En redes sociales: visual primero, texto breve y con personalidad

### Lo que SÍ hacemos
- Contenido visual-first (la imagen manda, el texto acompaña)
- Tips prácticos y accionables
- Nombres comunes de plantas (no solo científicos)
- Contextualizar al clima de Santiago/Chile
- CTAs suaves hacia productos cuando es natural
- Paleta de colores y tipografías de marca siempre

### Lo que NO hacemos
- Jerga botánica innecesaria
- Tono corporativo o frío
- Marketing genérico vacío
- Copiar contenido de otros viveros/tiendas
- Promesas exageradas sobre las plantas
- Presión de venta agresiva

---

## 12. Stack Tecnológico

| Herramienta | Uso |
|---|---|
| **Shopify** | E-commerce, gestión de productos, checkout |
| **Klaviyo** | Email marketing, automaciones, flujos post-compra |
| **Meta Ads** | Publicidad en Instagram y Facebook |
| **Judge.me** | Reviews de productos (evaluando migración a Loox) |
| **Selleasy** | Upselling y cross-selling |
| **Make (Integromat)** | Automatizaciones Shopify ↔ Klaviyo |
| **WhatsApp Business** | Atención al cliente, recuperación de carritos abandonados |

### Flujos Klaviyo (en orden de prioridad)
1. Abandoned Cart (1h → 24h → 48h)
2. Post-Purchase (inmediato → 3 días guía → 7 días review → 14 días cross-sell)
3. Welcome Series (bienvenida → historia → productos top)
4. Abandoned Checkout (30 min → 6h)
5. Winback (60–90 días sin comprar)
6. Browse Abandonment (2–4h)

**Flujo cítricos (configurado):** Triggered por "Placed Order" en Klaviyo con filtro colección "Cítricos". Entrega guía de cuidado PDF vía email. Subject: "Tu Guía de Cuidados ya está lista 🍋".

**Regla de ROI Klaviyo:** Debería generar 30–40x lo que se paga en revenue por email.

### Selleasy — Upselling
- "Frequently Bought Together": cada planta grande → maceteros compatibles
- Tags por tamaño: `macetero-30cm`, `macetero-40cm`, etc.
- Copy: "Dale el hogar que se merece" / "Esta planta necesita un macetero de 40cm — ¿agregamos uno?"

---

## 13. Marketing y Performance

### Meta Ads
- **CTR:** 2.57% – 6.67% (benchmark industria: 1–2%)
- **Conversión on-site:** ~0.045% (problema identificado: no es el ad, es el sitio post-clic)
- **Mejor performer:** anuncio de catálogo (6.386 impresiones, 4.67% CTR)
- **A/B testing activo:** campañas "Cítricos 1" vs "Cítricos 2"

### CRO Audit — Problemas Identificados (~22 de alta prioridad)
1. Typo en banner principal ("transforman transformr espacios")
2. Umbral envío gratis ($120.000) alto vs. ticket promedio
3. Error de precio en Yuca
4. Falta transparencia en costos de envío
5. Imágenes .heic pesadas (velocidad del sitio)
6. FAQ incompletas
7. Falta social proof visible en páginas de producto

### SEO
- Implementada guía de 60 días en 3 fases
- **Fase 1:** JSON-LD Schema, Judge.me Rich Snippets, meta descriptions, Search Console
- **Fase 2:** 4 blog posts estratégicos, internal linking
- **Fase 3:** 50+ reviews, link building local, GMB

**Keywords estratégicos:**
- Tier 1 (Comercial): "monstera deliciosa precio chile", "naranjo cara cara santiago", "plantas interior poca luz santiago"
- Tier 2 (Informacional): "cómo cuidar monstera en departamento", "calendario siembra santiago chile"
- Tier 3 (Local): "vivero plantas vitacura", "tienda plantas boutique santiago"

### Video y Creativos
- Herramientas: Kling AI, Runway Gen-4, HeyGen, CapCut (contenido UGC-style)
- Copy Meta aprobado: "Plantas que transforman tu casa" / "Del vivero a tu puerta"

---

## 14. Contenido y Blogs

### Estrategia
- Blog posts HTML embebidos en Shopify (template propio)
- Guías de cuidado por tipo de planta
- Ebook de cuidado de cítricos (entregado vía Klaviyo post-compra)
- Fichas de producto detalladas
- Video scripts para Reels

### Blogs Creados
- **Guía de Cuidados para Cítricos en Macetero:** luz, sustrato, riego, fertilización, poda, plagas. Productos enlazados: Sustrato Exterior, Vitalimás, Jabón Potásico, colección Frutales.
- **Guía de Cuidados para Palmeras de Interior (Kentia, Areca, Chamaedorea):** mismo template. Productos: Sustrato Interior, Vitalimás.

### Temas Recurrentes de Blog
- Plantas de interior para espacios con poca luz
- Cuidado estacional en Santiago
- Frutales en maceta / cítricos en terraza
- Plantas pet friendly
- Plantas para principiantes
- Decoración verde y plant styling

### 4 Blog Posts SEO Propuestos
1. "Las 10 Mejores Plantas de Interior para Departamentos en Santiago"
2. "Árboles Frutales para Jardines Pequeños: Guía Chile"
3. "Planta con Hojas Amarillas: Causas y Soluciones"
4. "Calendario de Jardinería Santiago: Qué Plantar Cada Mes"

---

## 15. Proyectos en Desarrollo

### Partnership La Dicha (restaurante, Vitacura)
- Restaurante en Alonso de Córdova 4355, Vitacura (CV Galería). Cocina fusión, 500+ m², 40K seguidores IG.
- Propuesta: Plantas Tole como "curador botánico" del restaurante
- Incluye: colección exclusiva "La Dicha by Plantas Tole", QR en carta, cenas botánicas, código "LADICHA" para tracking, regalos corporativos

### Gardenia (proyecto marketplace)
- Marketplace chileno: venta de plantas + servicios de jardinería + diagnóstico AI por foto
- Mercado: 1.516 viveros en Chile, 33% en RM. Cero competencia directa.
- Tech stack propuesto: Next.js 14 + PostgreSQL + Prisma + OpenAI GPT-4V + Stripe/Flow
- Roadmap: 16 semanas al MVP. Recomendación: empezar con Bubble.io para validar.
- Co-founder: abogado con background en agronomía. Gap: capacidad técnica.

---

## 16. Judge.me — Reviews

### Configuración
- Rich Snippets SEO activado
- Review request automático: 7 días después de entrega
- Incentivo: 10% descuento próxima compra por review con foto
- Nombre obligatorio en formulario
- Reviews Carousel en home y colecciones
- Review Widget completo en páginas de producto

### CSS Personalizado
- Estrellas: `#D3A150` (dorado)
- Cards: fondo `#FAF7F4` (crema) + borde izquierdo dorado
- Botones: redondeados (consistente con tip boxes de blogs)

---

## 17. WhatsApp — Recuperación de Carritos

**Tono definido:** Sutil, servicial, nunca agresivo. No mencionar "carrito abandonado" ni presionar.

**Template aprobado:**
> "Hola [nombre]! 🌿 Soy Diego de Plantas Tole. Noté tu interés en las [productos] — excelente elección, son plantas que transforman cualquier espacio. Si tienes alguna duda sobre su cuidado, tamaño o el despacho, quedo atento por acá 😊"

---

## 18. Sobre Diego (Fundador)

- Profesional de marketing digital y emprendedor
- Base en Santiago, Chile (Vitacura)
- Estilo de trabajo: directo, data-driven, orientado a ejecución
- Prefiere que Claude intente las tareas en vez de declinar
- Comparte analytics y data cruda para iterar rápido
- Intereses paralelos: atletismo híbrido (running + gym), audio, restauración de autos
- Perfil Upwork: "AI Automation | Shopify/Klaviyo Expert | Landing Pages"

---

## 19. Datos Estacionales — Santiago, Chile

- **Clima:** mediterráneo (veranos secos y calurosos, inviernos fríos y húmedos)
- **Temporada alta de plantas:** primavera (sep–nov) y principios de otoño (mar–abr)
- **Frutales cítricos:** plantación ideal en primavera, cosecha en otoño–invierno

---

## 20. Assets y URLs de Referencia

| Recurso | URL |
|---|---|
| Home | plantastole.cl |
| Interior | /collections/plantas-de-interior |
| Exterior | /collections/terraza-y-exterior |
| Frutales | /collections/frutales |
| Maceteros | /collections/macetero |
| Vitalimás | /collections/vitalimas |
| Únicas | /collections/formatos-unicos |
| Para Principiantes | /collections/para-principiantes |
| Pet Friendly | /collections/pet-friendly |
| Sobre Nosotros | /pages/sobre-plantas-tole |
| FAQ | /pages/preguntas-frecuentes |
| Contacto | /pages/contact |
| Blog | /blogs |
| **Logo** | `https://plantastole.cl/cdn/shop/files/LOGO_PLANTAS_TOLE_2.png?v=1718060662&width=160` |

---

## 21. SEO / Meta del Sitio

**Título:** "Plantastole - Tienda de Plantas y Decoración Verde para el Hogar – Plantas Tole"
**Descripción:** "Descubre Plantastole, tu tienda en línea para plantas de interior y exterior, árboles y soluciones de decoración verde. Embellece tus espacios con nuestra selección de plantas y árboles saludables."

---

> **Nota:** Este documento es un trabajo en progreso. Se enriquece con cada sesión de trabajo.
