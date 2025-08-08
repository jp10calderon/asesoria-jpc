# JPC Asesoría Financiera — Deploy rápido

Este ZIP contiene:
- `index.html` (landing Tailwind, responsive y con animaciones)

## Opción A: Netlify (súper fácil)
1) Ve a https://app.netlify.com/drop
2) Arrastra el ZIP o la carpeta descomprimida con `index.html`.
3) Netlify te dará un subdominio gratuito (puedes cambiarlo en *Site settings*).

## Opción B: GitHub Pages
1) Crea un repo en GitHub (p.ej. `jpc-site`) y sube `index.html`.
2) En **Settings → Pages**, elige **Source: Deploy from a branch**.
3) Branch: `main` y carpeta `/root`. Guarda.
4) Tu web quedará en `https://TU_USUARIO.github.io/jpc-site/`.

## Opción C: Vercel
1) Crea un proyecto nuevo en https://vercel.com (Importa tu repo de GitHub o arrastra la carpeta).
2) Vercel detectará un sitio estático y lo desplegará.
3) Conecta tu dominio en **Settings → Domains** si quieres usar uno propio.

---

**Notas**
- Tailwind usa CDN (`https://cdn.tailwindcss.com`), no requiere build.
- Si usas dominio propio, recuerda apuntar los DNS al proveedor (Netlify/Vercel/tu hosting).
- Para formulario real, luego conectamos Formspree/Notion/ConvertKit o similar.