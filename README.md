🖼️ Aplicaciones Digitales Educativas I — PWA `v1`

> Plataforma web progresiva (PWA) de apoyo a la asignatura **ADE I**  
> Medios Estáticos y Organización de la Información  
> Licenciatura en Informática · 3er Año · Plan E · Curso 2025-2026  
> Universidad de Informática "Jesús Montané Oropesa" (UIJ)

📋 Descripción general

Aplicación web progresiva (PWA) dedicada exclusivamente a **ADE I — Medios Estáticos**. Cubre los cinco temas del programa: desde los fundamentos de los sistemas de información digital hasta el texto, los recursos esquemáticos, la imagen digital bitmap y vectorial, la animación educativa y el proyecto final integrador.

Diseño editorial cálido con tipografía *DM Serif Display*, paleta **ámbar × coral × crema** sobre fondo oscuro. Visualmente diferenciada de ADE II para facilitar la identificación inmediata por parte de los estudiantes.

> Esta es la **versión independiente** de ADE I. También existe la versión unificada `ade` que integra ADE I y ADE II en una sola app.

🎯 Datos académicos

| Campo | Valor |
|---|---|
| **Asignatura** | ADE I — Aplicaciones Digitales Educativas I |
| **Enfoque** | Medios Estáticos y Organización de la Información |
| **Año académico** | 3er Año, Grupo único |
| **Carrera** | Licenciatura en Informática |
| **Plan de estudios** | Plan E |
| **Institución** | UIJ "Jesús Montané Oropesa" |
| **Profesor** | Ricardo Castillo Valdés |
| **Curso** | 2025-2026 |
| **Total de horas** | 34 horas (10h conferencias + 24h talleres) |

🗂️ Programa de la asignatura cubierto

Distribución:** 5 Conferencias (10 horas) + 12 Talleres Prácticos (24 horas)

Tema 1 — Introducción a los Sistemas de Aplicación y la Información Digital** *(4h)*
- Evolución de las aplicaciones digitales educativas (1970–hoy)
- Clasificación de la información digital: por naturaleza, temporalidad e interactividad
- Hipertexto, multimedia e hipermedia: definición y diferencias
- Tipos de aplicaciones educativas: texto, imagen, esquemas, animación
- Principios de diseño para la comunicación visual educativa

Tema 2 — El Texto Digital y los Recursos Esquemáticos** *(8h)*
- Formatos de texto: `.txt`, `.rtf`, `.docx`, `.md`, `.pdf`, `.html`
- Procesador de texto vs. editor de texto plano
- Tipografía educativa: serif/sans-serif, jerarquía, legibilidad
- El PDF como recurso educativo navegable: bookmarks e hipervínculos
- Recursos esquemáticos: mapa conceptual, mental, organigrama, diagrama de flujo, infografía, DAFO

Tema 3 — La Imagen Digital: Bitmap y Vectorial** *(8h)*
- Bitmap: píxel, resolución (DPI), profundidad de color, canal alfa
- Formatos: JPEG (lossy), PNG (lossless + transparencia), GIF (animación), WebP
- Vectorial: instrucciones matemáticas, escalado perfecto, SVG
- Bitmap vs. vectorial: cuándo usar cada uno
- Principios de diseño: contraste, paleta limitada, whitespace, accesibilidad

Tema 4 — Fundamentos de la Animación Educativa** *(6h)*
- Por qué animar en educación: propósito pedagógico
- Los 12 principios de Disney aplicados a educación
- Tipos: cuadro a cuadro, stop motion, GIF, CSS/web
- Pencil2D: fotogramas, FPS, onion skinning, capas
- GIF animado con GIMP: capas como fotogramas, retardo, optimización

Tema 5 — Proyecto Final Integrador ADE I** *(8h)*
- Componentes obligatorios: PDF navegable + recurso esquemático + animación/GIF
- Rúbrica: 5 criterios × 4 niveles (Insuficiente → Excelente)
- Metodología de trabajo: cronograma de 3 talleres de tutoría
- Exposición: 5-7 minutos (10% de la nota)

📱 Módulos de la aplicación

🏠 Inicio
Panel con estadísticas (5 temas, 15 documentos, 34h totales, 18 ejercicios disponibles). Acordeón expandible con los 5 temas: cada uno muestra los puntos de la conferencia y los talleres prácticos asociados.

🔧 Herramientas
6 fichas de herramientas de producción de **medios estáticos**, expandibles con detalle al tocar:

| Herramienta | Categoría | Licencia |
|---|---|---|
| **GIMP** | Imagen bitmap | Software libre |
| **Inkscape** | Imagen vectorial | Software libre |
| **CmapTools** | Mapas conceptuales | Software libre |
| **draw.io** | Diagramas y esquemas | Software libre |
| **Canva** | Diseño gráfico online | Freemium |
| **Pencil2D** | Animación 2D | Software libre |

Cada ficha incluye: descripción, uso educativo recomendado, formatos soportados, ventajas y consideraciones.

🎯 Ejercicios
Banco de **18 ejercicios** distribuidos en los 5 temas del programa:
- Opción múltiple
- Verdadero / Falso
- Completar la expresión

Sesiones aleatorias de **12 preguntas** del tema o temas seleccionados. El sistema registra porcentaje de aciertos y racha (🔥). Retroalimentación inmediata con explicación de cada respuesta.

📁 Materiales
15 documentos PDF descargables con filtros por categoría:

| Categoría | Nº | Documentos |
|---|---|---|
| **Conferencias** | 5 | Conf. 1 (T1) · Conf. 2 (T2) · Conf. 3 (T3) · Conf. 4 (T4) · Conf. 5 Proyecto Final |
| **Talleres** | 9 | T1 (T1) · T2, T3, T4 (T2) · T5, T6, T7 (T3) · T8, T9 (T4) |
| **Glosario** | 1 | Glosario ADE I y II — Términos Fundamentales |

Filtros: **Todos · Conferencias · Talleres · Glosario**

Cada documento se puede visualizar directamente en la app (iframe PDF) o descargar al dispositivo para uso completamente offline.

🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 / CSS3 / JavaScript (vanilla) | Aplicación completa sin frameworks |
| DM Serif Display + DM Sans + DM Mono | Tipografías (Google Fonts) |
| Web App Manifest | Instalación como PWA |
| Service Worker | Modo offline y caché |
| Base64 | 15 PDFs embebidos en el HTML |
| Blob URL API | Visualización y descarga de PDFs |
| ReportLab (Python) | Generación de los PDFs del material didáctico |

📂 Estructura del repositorio

ade1/
├── index.html          # Aplicación completa (179 KB, autocontenida)
├── manifest.json       # Manifiesto PWA (tema: amber #c85a00)
├── sw.js               # Service Worker para modo offline
├── icons/              # Iconos PWA — ícono con fotograma de imagen + sol
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   └── icon-512x512.png
└── README.md

Nota: Los 15 PDFs están embebidos en base64 dentro de `index.html`. La aplicación no requiere archivos adicionales ni conexión a internet tras la primera carga.

🚀 Despliegue

GitHub Pages
Settings → Pages → Branch: main → / (root) → Save
URL: https://usuario.github.io/ade1/

Netlify
Arrastrar la carpeta `ade1/` al panel de [netlify.com](https://netlify.com) → URL inmediata.

Servidor local
bash
python -m http.server 8080
# Abrir: http://localhost:8080

📲 Instalación como app en Android

1. Abrir la URL en **Chrome para Android**
2. Banner *"Añadir a pantalla de inicio"* → **Instalar**
3. Si no aparece: menú ⋮ → *"Añadir a pantalla de inicio"*
4. Ícono ámbar/coral en el escritorio, funciona sin internet

🔒 Requisitos técnicos

- Chrome 60+, Firefox 55+, Safari 11+ o equivalente
- HTTPS para Service Worker (automático en GitHub Pages y Netlify)
- Sin dependencias externas — funciona 100% offline tras primera carga
- Compatible con Android e iOS

🔗 Apps relacionadas

| Repositorio | Descripción |
|---|---|
| Esta app | ADE I independiente — medios estáticos |
| [`ade2`](../ade2/) | ADE II independiente — medios dinámicos |
| [`ade`](../ade/) | ADE I + II unificadas en una sola app |

📄 Licencia y uso

Recurso educativo de libre uso para fines académicos.  
Desarrollado con fines docentes para la UIJ "Jesús Montané Oropesa".



Generado con asistencia de Claude (Anthropic) · Marzo 2026*
