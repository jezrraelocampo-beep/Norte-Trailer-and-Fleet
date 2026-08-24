# NORTE TRAILER & FLEET — Sitio web

Sitio estático de una sola página (HTML/CSS/JS, sin dependencias ni build) para
NORTE TRAILER & FLEET, mantenimiento móvil de cajas secas en el área
metropolitana de Monterrey.

## Estructura del proyecto

```
norte-trailer-fleet/
├── index.html      → sitio completo (contenido, estilos y scripts inline)
├── vercel.json      → configuración de despliegue para Vercel
└── README.md
```

No hay `package.json` ni paso de build: es HTML puro, así que Vercel lo sirve
directamente como sitio estático.

## Cómo publicarlo en Vercel

**Opción A — Vercel CLI (más rápida):**
1. Instala la CLI si no la tienes: `npm i -g vercel`
2. Dentro de esta carpeta, corre: `vercel`
3. Sigue las preguntas (crea o vincula un proyecto). Para producción: `vercel --prod`

**Opción B — Panel web de Vercel:**
1. Sube esta carpeta a un repositorio de GitHub/GitLab/Bitbucket.
2. En [vercel.com](https://vercel.com) → "Add New Project" → importa el repositorio.
3. Framework Preset: **Other** (o "Static"). No se necesita configurar build ni output directory.
4. Deploy.

**Opción C — Arrastrar y soltar:**
1. En el dashboard de Vercel, usa la opción de subir carpeta directamente (drag & drop) sin pasar por Git.

## Pendientes antes de publicar

- La sección "Servicios" tiene 4 servicios de ejemplo (inspección preventiva,
  piso/estructura, puertas y sellos, cumplimiento normativo). Falta
  confirmar la lista completa de servicios reales del negocio para
  actualizarla.
- El número de WhatsApp ya está configurado: **81 1280 4515**.
- Las imágenes del sitio son solo formas/SVG; si quieres fotos reales, hay
  prompts de generación de imágenes ya preparados en la conversación.
