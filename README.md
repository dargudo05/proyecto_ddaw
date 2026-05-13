# Sound Home

> *Explora la música desde cómo te sientes hoy.*

**Sound Home** es una página web estática dedicada a la exploración de géneros musicales. Permite descubrir géneros, subgéneros y álbumes esenciales de forma organizada e intuitiva, sin abrumar al usuario — como un árbol genealógico musical construido para cualquier persona, sin importar su experiencia previa.

---

## Tabla de contenidos

- [Vista general](#vista-general)
- [Características](#características)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Secciones de la página](#secciones-de-la-página)
- [Géneros disponibles](#géneros-disponibles)
- [Sentimientos disponibles](#sentimientos-disponibles)
- [Cómo usar](#cómo-usar)
- [Contacto](#contacto)

---

## Vista general

Sound Home es una plataforma de consulta musical que organiza el universo de géneros desde dos perspectivas:

1. **Por Género** — exploración directa de 11 géneros principales con sus subgéneros, álbumes esenciales y artistas clave.
2. **Por Sentimiento** — recomendaciones musicales basadas en el estado emocional del momento.

---

## Características

- Navegación por géneros musicales con overlays de detalle
- Exploración por estados de ánimo (melancolía, energía, relajación, enojo, enfoque, romanticismo)
- Diccionario de Rock con instrumentación, subgéneros y géneros adyacentes
- Sección de testimonios de la comunidad
- Formulario de sugerencias de géneros y álbumes
- Ticker animado con géneros en scroll continuo
- Diseño completamente *responsive* con tema oscuro
- Sin dependencias externas — **cero frameworks JavaScript**

---

## Estructura del proyecto

```
soundhome/
└── index.html          Página única con todo el contenido (HTML, CSS y JS inline)
```

> **Nota:** Al ser un sitio estático de un solo archivo, no requiere servidor, proceso de build ni instalación de dependencias. Basta con abrir `index.html` en cualquier navegador moderno.

---

## Tecnologías utilizadas

- **HTML5** — estructura semántica y accesible
- **CSS3** — variables CSS (`custom properties`), CSS Grid, Flexbox, animaciones y `backdrop-filter`
- **JavaScript vanilla** — tab switching, overlays de detalle, scroll suave e `IntersectionObserver` para animaciones
- **Google Fonts** — tipografías *Bebas Neue*, *DM Sans* y *Space Mono*

---

## Secciones de la página

### Hero

Presentación principal con descripción del proyecto, acceso rápido a *Explorar por Género* y a la vista *Por Sentimiento*.

### Explorar Géneros

Dos pestañas:

- **Por Género** — grid de tarjetas interactivas. Al hacer clic en cualquier género se abre un overlay con álbumes esenciales, subgéneros y artistas clave.
- **Por Sentimiento** — tarjetas de estados de ánimo. Cada una abre un overlay con contenido editorial curado.

### Diccionario

Ficha extendida del género **Rock** con:

- Características y rasgos definitorios
- Estadísticas del género (subgéneros, año de origen, valoración)
- Instrumentación clave con barras visuales
- Los 5 álbumes esenciales
- Subgéneros destacados
- Mapa de géneros adyacentes con descripciones comparativas

### Comunidad & Reseñas

Testimonios reales de usuarios de distintas ciudades de Ecuador sobre cómo descubrieron un género a través de Sound Home.

### Contacto

Formulario de sugerencias para proponer géneros, álbumes, correcciones o testimonios. También incluye las métricas del proyecto en números.

---

## Géneros disponibles

Cada género abre un panel de detalle completo con álbumes, subgéneros y artistas:

- 🎸 **Rock** — Grunge · Alt · Clásico · Post-rock *(12 subgéneros)*
- 🎤 **Hip-Hop** — Trap · Boom Bap · Conscious · Cloud *(9 subgéneros)*
- 🎹 **Electrónica** — House · Techno · Ambient · Drum & Bass *(15 subgéneros)*
- 🎷 **Jazz** — Bebop · Fusion · Smooth · Neo-soul *(8 subgéneros)*
- 🤘 **Metal** — Death · Black · Prog · Nu-metal · Doom *(11 subgéneros)*
- 🎵 **R&B** — Soul · Neo-soul · Contemporary · Funk *(7 subgéneros)*
- 🌿 **Folk** — Indie folk · Americana · Celtic · Singer-songwriter *(6 subgéneros)*
- 🎻 **Clásica** — Barroco · Romántico · Contemporáneo · Minimalismo *(5 subgéneros)*
- 🎶 **Pop** — Synth-pop · Electropop · Art pop · K-pop *(10 subgéneros)*
- 🌊 **Reggae** — Dancehall · Dub · Reggaeton · Ska *(5 subgéneros)*
- ⚡ **Punk** — Hardcore · Post-punk · Emo · Pop-punk *(7 subgéneros)*

---

## Sentimientos disponibles

Cada sentimiento incluye álbumes curados, géneros relacionados, artistas clave y sentimientos adyacentes:

| Emoji | Sentimiento | Géneros asociados |
| ----- | ----------- | ----------------- |
| 🌧️ | Melancolía | Post-rock, Slowcore, Indie folk, Shoegaze |
| ⚡ | Energético | Punk, Drum & Bass, Metal, Trap |
| 🌊 | Relajado | Ambient, Bossa Nova, Acoustic, Lo-fi |
| 🔥 | Enojado | Hardcore, Noise Rock, Industrial, Grindcore |
| 🎯 | Enfocado | Minimalismo clásico, Lo-fi hip hop, Jazz contemporáneo, Ambient |
| 💜 | Romántico | R&B contemporáneo, Dream pop, Soul clásico, Bolero |

---

## Cómo usar

1. Descargar o clonar el repositorio.
2. Abrir `index.html` directamente en el navegador — no requiere servidor local.
3. Navegar por las secciones usando el menú superior o los botones del hero.
4. Hacer clic en cualquier tarjeta de género o sentimiento para abrir su detalle completo.
5. Presionar `Esc` o el botón *← Volver* para cerrar cualquier overlay.

---

## Contacto

¿Sugerencias de géneros, álbumes esenciales o correcciones?

✉ [daniel.argudo@uees.edu.ec](mailto:daniel.argudo@uees.edu.ec)

---

* 2025 Sound Home — Plataforma de géneros musicales*
