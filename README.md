# Creer para Crear

Aplicación de estudio bíblico por Sofia (sin tilde).

---

## Cómo subir a GitHub y publicar en Netlify

### Paso 1 — Subir a GitHub

1. Ve a [github.com](https://github.com) e inicia sesión
2. Haz clic en el botón verde **"New"** (o **"+"** > **"New repository"**)
3. Ponle nombre al repositorio, por ejemplo: `creer-para-crear`
4. Márcalo como **Public**
5. **No** marques "Add a README file" (ya tienes uno)
6. Haz clic en **"Create repository"**
7. GitHub te mostrará instrucciones — elige **"upload an existing file"**
8. Arrastra los archivos de esta carpeta (`index.html`, `netlify.toml`, `.gitignore`, `README.md`)
9. Haz clic en **"Commit changes"**

### Paso 2 — Publicar en Netlify

1. Ve a [netlify.com](https://netlify.com) e inicia sesión (puedes hacerlo con tu cuenta de GitHub)
2. Haz clic en **"Add new site"** > **"Import an existing project"**
3. Elige **"Deploy with GitHub"**
4. Autoriza Netlify para acceder a tus repositorios
5. Busca y selecciona el repositorio `creer-para-crear`
6. En la configuración de build, deja todo en blanco (no hace falta build command ni publish directory — Netlify lo detecta solo)
7. Haz clic en **"Deploy site"**
8. En unos segundos tendrás una URL como `https://creer-para-crear.netlify.app`

### Actualizar el sitio

Cada vez que subas cambios a GitHub (reemplazando el `index.html`), Netlify **re-desplegará automáticamente** en segundos.

---

Hecho con amor por Sofia · 2026
