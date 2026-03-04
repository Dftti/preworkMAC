# Plantastole — Contexto de Marca y Tienda

> Archivo de referencia para crear contenido, blogs, campañas y herramientas para Plantastole.
> Última actualización: Marzo 2026

---

## 1. Identidad de Marca

**Nombre:** Plantas Tole / Plantastole
**Slogan:** "Plantas que transforman espacios"
**Fundación:** Junio 2023
**Fundadores:** Felipe y Diego (amigos de la infancia)

**Historia de la marca:**
Felipe es vivero tercera generación, con experiencia familiar profunda en plantas ornamentales. Diego tiene background en diseño. Juntos crearon Plantastole para ofrecer plantas grandes, sanas y listas para decorar, eliminando el ensayo y error de elegir plantas para el hogar chileno.

**Propuesta de valor:**
- Plantas de gran formato, listas para decorar
- Selección personalizada y asesoría real (WhatsApp, Instagram)
- Garantía de 14 días en plantas
- Atención boutique: cercana, detallista, con seguimiento

**Plataforma e-commerce:** Shopify

---

## 2. Colores

### Paleta Principal

| Nombre | HEX | RGB | Uso |
|---|---|---|---|
| Verde Bosque (principal) | `#1B321B` | `27, 50, 27` | Texto, navegación, íconos, botón de texto |
| Durazno / Tan Cálido | `#F6CFB2` | `246, 207, 178` | Botones CTA, acentos cálidos |
| Blanco | `#FFFFFF` | `255, 255, 255` | Fondo principal |
| Gris Medio | `#BFBFBF` | `191, 191, 191` | Contraste de fondo, elementos secundarios |
| Amarillo Estrellas | `#F8E714` | `248, 231, 20` | Rating/reseñas (Judge.me) |

### Variables CSS (`:root`)

```css
--color-foreground: 27,50,27;           /* #1B321B */
--color-background: 255,255,255;        /* #FFFFFF */
--color-background-contrast: 191,191,191; /* #BFBFBF */
--color-button: 246,207,178;            /* #F6CFB2 */
--color-button-text: 27,50,27;          /* #1B321B */
--color-badge-border: 27,50,27;         /* #1B321B */
--color-badge-background: 255,255,255;  /* #FFFFFF */
--color-link: 255,255,255;              /* #FFFFFF */
--color-secondary-button: 255,255,255;  /* #FFFFFF */
--jdgm-primary-color: #1B321B;
--jdgm-star-color: #F8E714;
```

---

## 3. Tipografías

| Tipo | Familia | Peso | Uso |
|---|---|---|---|
| Headings | `"Playfair Display", serif` | 400 | Títulos, destacados, nombres de productos |
| Body | `Lato, sans-serif` | 400 / 700 | Cuerpo de texto, descripciones, navegación |
| Fallbacks | Arial, "Nunito Sans", Helvetica | — | Compatibilidad |

### Variables CSS

```css
--font-heading-family: "Playfair Display", serif;
--font-heading-weight: 400;
--font-heading-scale: 1.0;
--font-body-family: Lato, sans-serif;
--font-body-weight: 400;
--font-body-weight-bold: 700;
--font-body-scale: 1.0;
```

**Notas de estilo tipográfico:**
- Playfair Display da un tono elegante y boutique
- Lato asegura legibilidad en móvil y escritorio
- No usar más de 2 familias en piezas de comunicación

---

## 4. Tienda Física

**Dirección:** Tabancura 1610, Vitacura, Santiago, Chile
**Horario:**
- Martes a Viernes: 10:00 – 19:00
- Sábado: 10:00 – 16:30
- Domingo y Lunes: Cerrado

---

## 5. E-Commerce y Operación

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

### Categorías de Productos

**Plantas Interior:**
- Colecciones generales de interior

**Plantas Exterior:**
- Pleno Sol / Semisol
- Semisombra
- Con Flor
- Frutales
- Helechos

**Colecciones Especiales:**
- Únicas y Exclusivas (formatos grandes, especiales)
- Para Principiantes
- Pet Friendly

**Otros Productos:**
- Maceteros
- Cuidado de tus Plantas

### Ejemplos de Precios (CLP)

| Producto | Precio |
|---|---|
| Kentia | $28.090 – $32.990 |
| Longifolio | $34.990 |
| Cordatum | $24.990+ |
| Manto de Eva XL | $219.990 – $299.990 |
| Strelitzia Reginae | $99.990 – $109.990 |
| Naranjo Cara Cara (M) | $64.990 – $84.990 |
| Limequat | $87.990 – $109.990 |
| Mandarino (L) | $74.990 – $99.990 |

### Reseñas
- Plataforma: **Judge.me**
- Rating promedio: **4.82 / 5.0** (49+ reseñas verificadas)

---

## 6. Proyectos Comerciales

Plantastole ofrece diseño y mantención para:
- Terrazas residenciales
- Restaurantes
- Oficinas

Servicios: selección personalizada, instalación y coordinación de mantención/reemplazo.

---

## 7. Navegación del Sitio

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
Sobre Nosotros
Contacto
```

---

## 8. SEO / Meta

**Título:** "Plantastole - Tienda de Plantas y Decoración Verde para el Hogar – Plantas Tole"
**Descripción:** "Descubre Plantastole, tu tienda en línea para plantas de interior y exterior, árboles y soluciones de decoración verde. Embellece tus espacios con nuestra selección de plantas y árboles saludables. Envíos rápidos y atención al cliente excepcional."

---

## 9. Diseño UI / Especificaciones Técnicas

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

## 10. Tono de Voz y Estilo de Comunicación

- **Cercano y humano:** como un amigo que sabe de plantas
- **Sin tecnicismos innecesarios:** accesible para cualquier nivel de experiencia
- **Con personalidad:** no genérico, refleja la historia de Felipe y Diego
- **Educativo sin ser pedante:** guía al cliente, no lo abruma
- **Chileno:** usar lenguaje natural del español chileno cuando corresponda

---

## 11. Preguntas Abiertas / Cosas por Confirmar

> Estas secciones se pueden enriquecer en conversaciones futuras:

- [ ] ¿Cuáles son exactamente los blogs que hemos creado? (temas, estructura, tono)
- [ ] ¿Hay una paleta extendida de colores para redes sociales o piezas offline?
- [ ] ¿Usan algún color secundario adicional más allá del verde y durazno?
- [ ] ¿Tienen lineamientos de foto/imagen (estilo fotográfico)?
- [ ] ¿Cuál es la frecuencia de publicación en redes sociales?
- [ ] ¿Hay campañas estacionales relevantes (primavera, verano, etc.)?

