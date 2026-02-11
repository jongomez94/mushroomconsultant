# Landing Page — Consultor de Granjas de Hongos | Jonathan

Landing page de una sola página (HTML + CSS) para posicionar como consultor #1 en granjas de cultivo de hongos gourmet y medicinales en El Salvador y Centroamérica.

## Contenido

- **Hero** con título, subtítulo, imagen y CTA principal
- **Sobre mí** con experiencia y logros
- **Servicios** (diseño de granjas, asesoría, capacitación, optimización, acompañamiento)
- **Testimonios** de clientes
- **CTA final** con enlace a consulta gratuita (WhatsApp)

## Cómo usar

1. **Editar número de WhatsApp**: En `index.html`, busca `503XXXXXXXX` y reemplázalo por tu número con código de país (ej: `50371234567`).
2. **Opcional**: Sustituir las URLs de imágenes de Unsplash por tus fotos reales (hero, sobre mí, testimonios).

## Despliegue en Netlify

- **Opción A**: Arrastra la carpeta del proyecto a [Netlify Drop](https://app.netlify.com/drop).
- **Opción B**: Conecta este repositorio en Netlify; la raíz del sitio es la carpeta del proyecto y la página de inicio es `index.html` (configuración por defecto).

No se requiere build: es sitio estático.

## Subir a GitHub

```bash
git init
git add .
git commit -m "Landing consultor granjas de hongos"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin main
```

Luego en Netlify: **Add new site → Import an existing project → GitHub** y selecciona este repo.
