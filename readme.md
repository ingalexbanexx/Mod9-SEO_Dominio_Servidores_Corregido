# Optimización de SEO On-Page y Accesibilidad Web

Repositorio correspondiente a la entrega de optimización de **SEO On-Page** y **Accesibilidad Web** para el sitio web de soluciones informáticas y desarrollo web de **Alexbanexx (Ing. Marcelo Alejandro Banega)**.

## Objetivos Implementados

- **SEO On-Page**: Configuración de etiquetas de alto valor semántico, eliminación de redundancias genéricas e inclusión de metadatos optimizados.
- **Meta Description**: Inclusión de descripciones únicas, concisas y orientadas a la conversión (120-155 caracteres) en las 5 páginas del sitio.
- **Palabras Clave (Keywords)**: Integración natural de términos de búsqueda estratégicos en `<title>`, `<h1>`, `<h2>` y texto de párrafos sin incurrir en *keyword stuffing*.
- **Accesibilidad (a11y)**:
  - Textos descriptivos en el atributo `alt` de todas las imágenes para lectores de pantalla.
  - Relación de contraste de color superior a la directiva WCAG 2.1 nivel AA (mínimo 4.5:1).
  - Anillos de enfoque visibles (`:focus-visible`) para navegación fluida mediante teclado.
  - Un único encabezado `<h1>` por página con jerarquía lógica estricta (`<h1>` → `<h2>` → `<h3>`).

## Checklist de Criterios de Aceptación

| Criterio | Implementación | Estado |
| :--- | :--- | :---: |
| **Repositorio Público** | Código publicado en modo público en GitHub sin restricciones. | ✅ Cumplido |
| **Meta Description en `<head>`** | Descripción individual y personalizada en cada uno de los 5 archivos HTML. | ✅ Cumplido |
| **Integración de Keywords** | Palabras clave incorporadas en títulos, encabezados y párrafos clave de forma orgánica. | ✅ Cumplido |
| **Atributos `alt` Descriptivos** | Todas las imágenes poseen descripciones detalladas del contenido que representan. | ✅ Cumplido |
| **Contraste Texto/Fondo** | Contraste de texto principal `#f3f4f6` y atenuado `#cbd5e1` sobre fondo `#0a0e17` (> 7:1). | ✅ Cumplido |
| **Jerarquía Semántica** | Exactamente un `<h1>` por documento, complementado por `<h2>` para bloques temáticos. | ✅ Cumplido |
| **Nombres de Archivos** | Rutas y nombres de archivos descriptivos, en minúsculas y sin caracteres conflictivos. | ✅ Cumplido |

## Resumen de Metadatos por Página

| Archivo | Título Optimizado (`<title>`) | Palabras Clave Principales |
| :--- | :--- | :--- |
| `index.html` | Desarrollo Web Profesional y Software en Jujuy \| Alexbanexx | Desarrollo web, software en Jujuy, arquitectura digital |
| `pages/sobre-mi.html` | Sobre Mí \| Perfil Profesional de Marcelo Banega | Marcelo Banega, ingeniero informático, frontend |
| `pages/servicios.html` | Servicios de Desarrollo Web e Infraestructura \| Alexbanexx | Servicios frontend, auditoría SEO, redes y servidores |
| `pages/proyectos.html` | Portafolio de Proyectos de Desarrollo Web \| Alexbanexx | Portafolio web, casos de éxito, sitios accesibles |
| `pages/contacto.html` | Contacto y Presupuestos de Desarrollo Web \| Alexbanexx | Presupuesto desarrollo web, contacto Jujuy |

## Estructura del Directorio

entrega-seo-accesibilidad/
├── index.html                  # Página principal con SEO y mapa interactivo
├── README.md                   # Documentación técnica de SEO y accesibilidad
├── pages/                      # Páginas secundarias optimizadas
│   ├── sobre-mi.html           # Perfil profesional y principios de accesibilidad
│   ├── servicios.html          # Catálogo de especialidades técnicas
│   ├── proyectos.html          # Portafolio de sistemas desarrollados
│   └── contacto.html           # Formulario accesible con labels asociados
├── styles/
│   └── styles.css              # Estilos con verificación de contraste WCAG AA
└── images/                     # Recursos gráficos con nombres descriptivos
    ├── logo.png
    ├── banner-inicio.jpg
    ├── perfil.jpg
    ├── servicios.jpg
    ├── proyectos.jpg
    └── contacto.jpg

## Buenas Prácticas Aplicadas

1. **Sin Meta Keywords Obsoletas**: Se prescindió de `<meta name="keywords">` siguiendo los estándares oficiales de indexación modernos de Google.
2. **Formularios Accesibles**: Cada campo (`<input>`, `<textarea>`) se encuentra estrictamente asociado a su `<label>` mediante el atributo `for` e `id` correspondiente.
3. **Imágenes Semánticas**: Todas las imágenes se integran dentro de estructuras `<figure>` acompañadas de su respectivo `<figcaption>`.

## Autor:
Ing. Marcelo Alejandro Banega | AlexBanexx IT Soluciones Informáticas
2026