# Cómo publicar

El repo ya está listo para deploy. Elegí una opción.

## Opción A — Netlify Drop (la más rápida, sin GitHub)
1. Entrá a https://app.netlify.com/drop
2. Arrastrá **toda la carpeta del proyecto** a la página.
3. Te da una URL pública (`algo.netlify.app`). Compartila. ✅

## Opción B — GitHub + GitHub Pages (deploy automático)
1. Creá un repo vacío en https://github.com/new (sin README ni .gitignore).
2. Subí el proyecto:
   ```bash
   git remote add origin https://github.com/TU-USUARIO/pendulo-fc.git
   git push -u origin main
   ```
3. En el repo: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. Listo: cada `git push` a `main` (o cada **Release** que publiques) republica solo.
   - La app queda en `https://TU-USUARIO.github.io/pendulo-fc/`

## Opción C — GitHub + Netlify (deploy automático)
1. Subí el repo a GitHub (pasos 1–2 de la opción B).
2. En Netlify: **Add new site → Import from GitHub** → elegí el repo.
3. Sin build. Cada push republica solo (usa `netlify.toml`).

---
**Los datos** (planteles, fotos, jugadas, stats) viven en el navegador de cada persona.
Para pasar los tuyos: **💾 Descargar backup** en tu compu → **⬆️ Importar backup** en la web.
