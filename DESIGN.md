---
version: alpha
name: DDESIGN # REVISAR: nombre definitivo de tu marca personal
description: >-
  Sistema de diseño para la marca personal de una diseñadora (portafolio de
  diseño). Estética contemporánea, cálida y expresiva: composiciones limpias,
  espacios amplios y una paleta suave con contrastes cálidos. Mobile-first,
  aplicable a branding, editorial, contenido digital y UX.
colors:
  primary: "#E0846E"          # coral cálido — CTA, acentos, títulos y recursos gráficos
  secondary: "#DD7182"        # rosa frambuesa — hover, estados activos y detalles editoriales
  tertiary: "#F4D17F"         # amarillo miel — destacados, etiquetas y fondos luminosos
  lavender: "#CBABCE"         # lavanda suave — tarjetas, campos y bloques secundarios
  lilac: "#EAE7F3"            # lila muy claro — fondo alterno y zonas de descanso visual
  surface: "#FFFFFF"          # REVISAR: blanco dominante, hex inferido (el doc no da valor)
  on-surface: "#2B2B2B"       # color principal de texto y contraste
  on-surface-muted: "#5F5F5F" # placeholders y texto secundario
  overlay: "#2B2B2B"          # usa on-surface con 45-55% de opacidad en overlays
typography:
  display:
    fontFamily: "Montserrat"
    fontSize: 64px
    fontWeight: 700
    lineHeight: 72px
  h1:
    fontFamily: "Montserrat"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 56px
  h2:
    fontFamily: "Montserrat"
    fontSize: 36px
    fontWeight: 700
    lineHeight: 44px
  h3:
    fontFamily: "Montserrat"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 36px
  h4:
    fontFamily: "Montserrat"
    fontSize: 22px
    fontWeight: 600
    lineHeight: 30px
  body-large:
    fontFamily: "Montserrat"
    fontSize: 20px
    fontWeight: 400
    lineHeight: 32px
  body:
    fontFamily: "Montserrat"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 28px
  label-large:
    fontFamily: "Montserrat"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 22px
  body-small:
    fontFamily: "Montserrat"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 21px
  label:
    fontFamily: "Montserrat"
    fontSize: 12px
    fontWeight: 600
    lineHeight: 18px
rounded:
  sm: 14px
  md: 16px
  lg: 20px              # REVISAR: doc indica 16-24px para imágenes destacadas; tomé 20px
  xl: 24px
  pill: 999px
  circle: 9999px
spacing:
  2xs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 40px
  3xl: 48px
  4xl: 64px
  5xl: 80px
  6xl: 96px
  7xl: 128px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-surface}"
    typography: "{typography.label-large}"
    rounded: "{rounded.pill}"
    padding: "12px 24px"
  button-primary-hover:
    backgroundColor: "{colors.secondary}"
  button-primary-active:
    backgroundColor: "{colors.primary}"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.label-large}"
    rounded: "{rounded.pill}"
    padding: "12px 24px"
  button-secondary-hover:
    backgroundColor: "{colors.lilac}"
  button-accent:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.on-surface}"
    typography: "{typography.label-large}"
    padding: "12px 24px"
  button-rect:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-surface}"
    typography: "{typography.label-large}"
    rounded: "{rounded.sm}"
    padding: "12px 20px"
  card-project:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.md}"
    padding: "{spacing.lg}"
  card-editorial:
    backgroundColor: "{colors.lavender}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    padding: "{spacing.lg}"
  card-curriculum:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    padding: "{spacing.lg}"
  field:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.label-large}"
    rounded: "{rounded.sm}"
    padding: "14px 16px"
  field-placeholder:
    textColor: "{colors.on-surface-muted}"
    typography: "{typography.label-large}"
  overlay:
    backgroundColor: "{colors.overlay}"
  chip:
    backgroundColor: "{colors.lilac}"
    textColor: "{colors.on-surface}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "8px 14px"
  chip-active:
    backgroundColor: "{colors.primary}"
  nav-link:
    textColor: "{colors.on-surface}"
    typography: "{typography.label-large}"
  nav-link-active:
    textColor: "{colors.primary}"
---

# Design System — Marca personal · Portafolio de diseño

## Overview

Estética contemporánea, cálida y expresiva que equilibra claridad, curiosidad y sensibilidad visual. Cada proyecto debe sentirse cuidado sin volverse rígido: una identidad que se mueve entre branding, editorial, contenido digital y UX sin perder coherencia.

La comunicación se apoya en composiciones limpias, espacios amplios y una paleta suave con contrastes cálidos. Profesional pero cercano, con momentos de energía a través del coral y el rosa frambuesa, equilibrados por amarillo miel, lavanda y lila claro. En una frase: **diseño con intención, color y curiosidad, sin saturar la experiencia**.

## Colors

La paleta parte de cinco tonos principales. El blanco se mantiene como fondo dominante y los colores más claros se reservan para zonas de apoyo, evitando que toda la interfaz se vuelva demasiado pastel.

- **Primary** ({colors.primary} — coral cálido): CTA, acentos, títulos y recursos gráficos.
- **Secondary** ({colors.secondary} — rosa frambuesa): hover, estados activos y detalles editoriales.
- **Tertiary** ({colors.tertiary} — amarillo miel): destacados, etiquetas y fondos luminosos.
- **Lavender** ({colors.lavender} — lavanda suave): tarjetas, campos y bloques secundarios.
- **Lilac** ({colors.lilac} — lila muy claro): fondo alterno y zonas de descanso visual.
- **Surface** ({colors.surface}): fondo dominante. *(REVISAR: hex inferido)*
- **On-surface** ({colors.on-surface}): texto principal y contraste global.
- **On-surface-muted** ({colors.on-surface-muted}): placeholders y texto secundario.
- **Overlay** ({colors.overlay}): tintas de overlay con 45–55% de opacidad.

Nota de legibilidad: para texto pequeño y párrafos usar principalmente {colors.on-surface} sobre blanco o fondos claros. Coral y rosa frambuesa funcionan mejor como acentos; amarillo miel, lavanda y lila son ideales para fondos, etiquetas y bloques de apoyo.

## Typography

Familia única: **Montserrat** en toda la experiencia, con archivos en `assets/fonts/Montserrat/static/` (`.ttf` y `.woff2` para web). La personalidad se construye variando peso, tamaño, espacio y color, sin introducir una segunda familia, para que las imágenes de los proyectos sean las protagonistas.

Escala escritorio (valores de prueba):

| Token | Tamaño | Interlineado | Peso | Uso |
| --- | --- | --- | --- | --- |
| {typography.display} | 64px | 72px | 700–800 | Titulares muy breves, nombre o frase de apertura |
| {typography.h1} | 48px | 56px | 700 | Título principal de cada página o proyecto |
| {typography.h2} | 36px | 44px | 700 | Secciones principales |
| {typography.h3} | 28px | 36px | 600 | Subsecciones y bloques internos |
| {typography.h4} | 22px | 30px | 600 | Tarjetas y pequeños encabezados |
| {typography.body-large} | 20px | 32px | 400–500 | Introducciones y textos de presentación |
| {typography.body} | 18px | 28px | 400 | Casos de estudio y descripciones |
| {typography.label-large} | 16px | 22px | 500–600 | Menú, CTA, filtros y enlaces |
| {typography.body-small} | 14px | 21px | 400–500 | Metadatos, fechas, categorías y notas |
| {typography.label} | 12px | 18px | 600 | Chips o microetiquetas; con moderación |

Móvil: display baja a 40–44px, H1 a 34–36px, H2 a 28–30px y cuerpo a 16–17px. El cuerpo no debe bajar de 16px. Para párrafos largos usar Montserrat en peso 400 con interlineado amplio, para que la textura no se sienta pesada.

## Layout

El espaciado se basa en una unidad de 8px con la escala {spacing.2xs}–{spacing.7xl}: 4, 8, 12, 16, 24, 32, 40, 48, 64, 80, 96 y 128px. La página debe sentirse aireada y dejar respirar cada proyecto.

- Ancho máximo de contenido: 1280–1360px centrado; imágenes hero pueden extenderse a ancho completo.
- Escritorio: rejilla de 12 columnas; márgenes laterales de 64–96px ({spacing.4xl}–{spacing.6xl}).
- Tableta: rejilla de 6–8 columnas; márgenes de 32–48px ({spacing.xl}–{spacing.3xl}).
- Móvil: 1 columna; márgenes de 20–24px. *(REVISAR: 20px no está en la escala de 8px; consideré abrir a {spacing.lg}/24px)*
- Separación entre secciones grandes: 80–120px escritorio y 56–72px móvil. *(normalizado a {spacing.5xl}–{spacing.7xl} y {spacing.2xl}–{spacing.4xl} en la escala)*
- Separación interna de tarjetas: 24–32px ({spacing.lg}–{spacing.xl}); botones: 12–16px vertical y 20–28px horizontal.

Mobile-first: la navegación y las transiciones se sienten suaves, sin movimientos agresivos ni cambios repentinos. Zonas táctiles mínimas de ≈ 44×44px. En móvil el menú puede volverse hamburguesa, pero conserva acceso directo a Proyectos, Sobre mí y Contacto.

## Elevation & Depth

La interfaz se mantiene principalmente plana para que el color, la tipografía y las imágenes creen jerarquía. Las sombras aparecen solo en interacción o cuando un elemento necesita despegarse del fondo.

- Nivel base: sin sombra para navegación, campos y tarjetas en reposo.
- Hover de tarjeta: `0 8px 24px rgba(43, 43, 43, 0.08)`.
- Flotante o modal: `0 16px 40px rgba(43, 43, 43, 0.14)`.
- Overlay: {colors.overlay} con 45–55% de opacidad, para mantener contraste sin endurecer la paleta.

## Shapes

Formas suaves y contemporáneas: un radio medio en tarjetas y botones, y el círculo como motivo recurrente por la construcción visual de la paleta. Amable sin caer en una estética infantil.

- Tarjetas y contenedores: {rounded.md}.
- Imágenes destacadas: {rounded.lg}–{rounded.xl} (16–24px), según composición. *(REVISAR: token lg = 20px inferido)*
- Botones: {rounded.pill} (píldora) o {rounded.sm} (14–16px rectangulares).
- Chips y filtros: {rounded.pill}.
- Avatares, indicadores y recursos gráficos pequeños: círculo perfecto ({rounded.circle}).

## Components

Simple y reconocible. La personalidad está en el color, el movimiento suave y la composición, no en decoración innecesaria. Propiedades extra (bordes, sombras, desplazamientos) se aplican por componente y se detallan abajo.

- **Botón principal** ({components.button-primary}): fondo {colors.primary}, texto {colors.on-surface} en Montserrat 600 a 16px, píldora. En hover puede pasar a {colors.secondary} y desplazarse 1–2px hacia arriba. Activo: vuelve al coral base y reduce levemente la escala. Para texto pequeño se prefiere el tono oscuro (mejor contraste que blanco sobre estos colores).
- **Botón secundario**: fondo {colors.surface} (visiblemente equivalente a transparente sobre fondo claro), borde de 1.5px {colors.on-surface} y texto {colors.on-surface}. En hover puede rellenarse con {colors.lilac} o {colors.lavender}. El botón de acento usa {colors.tertiary} con texto oscuro para acciones de menor jerarquía.
- **Tarjetas de proyecto** ({components.card-project}): imagen grande primero, luego categoría, título y descripción breve. Fondo blanco o {colors.lilac}, radio {rounded.md} y sin borde visible en reposo. En hover la imagen puede escalar 1.02–1.04 y la tarjeta gana sombra muy suave. Bloques editoriales: alternar {colors.lavender} o {colors.tertiary} con texto {colors.on-surface}.
- **Navegación y enlaces**: Montserrat 500 a 16px ({typography.label-large}) en {colors.on-surface}. Activo: punto, subrayado corto o cambio a {colors.primary}. Enlaces dentro del texto se mantienen oscuros y se subrayan en hover con {colors.secondary} para no depender solo del color.
- **Campos y formularios** ({components.field}): fondo blanco, borde 1.5px {colors.lavender}, texto {colors.on-surface} a 16px y radio {rounded.sm}. Al enfocar, el borde pasa a {colors.primary} con halo muy suave en {colors.lilac}. Etiquetas arriba del campo en Montserrat 600 a 14px. Placeholders en {colors.on-surface-muted}.
- **Etiquetas y filtros** ({components.chip}): fondo {colors.lilac} o {colors.lavender} con texto {colors.on-surface} a 12–14px y peso 600. Activo: {colors.primary} o {colors.secondary} con texto oscuro. Espaciado: 8px vertical × 14px horizontal.
- **Sección hero**: nombre, frase breve y selección visual clara de proyectos. Fondo blanco con un gran recurso circular de color, o composición fotográfica limpia. Padding vertical: 96–128px escritorio, 64–80px móvil. Display a 64px escritorio y 40–44px móvil.
- **Tarjetas de educación y experiencia**: fondos de color sólido para diferenciar lo curricular — {colors.secondary} o {colors.primary} con texto {colors.on-surface} en bloques principales; {colors.tertiary}, {colors.lavender} o {colors.lilac} en los secundarios. Evitar párrafos largos con poco contraste: los tonos más saturados funcionan en títulos, cifras y detalles gráficos.
- **Íconos y recursos gráficos**: simples, de trazo consistente y preferentemente en {colors.on-surface}. Coral y rosa frambuesa pueden aparecer en estados interactivos. Círculos, puntos y formas orgánicas pueden usar {colors.tertiary}, {colors.lavender} o {colors.lilac} como apoyo, sin competir con las imágenes.
- **Movimiento**: scroll suave, transiciones de 200–350ms con curvas _ease-out_, apariciones discretas y hovers con desplazamientos mínimos. Un cursor personalizado solo si sigue siendo fácil de entender y no oculta estados importantes. Si el sistema solicita reducir movimiento, simplificar o desactivar animaciones.

## Do's and Don'ts

- **Do** usar {colors.on-surface} como color principal de texto y contraste.
- **Do** mantener el blanco como fondo dominante y usar {colors.lilac}/{colors.lavender} por bloques.
- **Do** usar {colors.primary} y {colors.secondary} para interacción y acentos importantes.
- **Do** mantener al menos 16px en texto de lectura.
- **Do** dejar 80–120px entre secciones importantes en escritorio.
- **Do** usar {colors.tertiary}, {colors.lavender} y {colors.lilac} para jerarquía suave.
- **Do** dejar que la fotografía y los proyectos sean protagonistas.
- **Don't** usar coral o rosa frambuesa con texto blanco pequeño; el contraste es insuficiente.
- **Don't** convertir todos los fondos en lavanda o lila; deja respirar la interfaz.
- **Don't** usar más de tres colores de la paleta simultáneamente en un mismo bloque.
- **Don't** reducir el cuerpo por debajo de 16px.
- **Don't** usar sombras pesadas ni bordes oscuros en todas las tarjetas.
- **Don't** usar animaciones bruscas o rebotes excesivos.
- **Don't** añadir ornamentos si no ayudan a la jerarquía o navegación.