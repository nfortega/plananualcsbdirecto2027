# SIGCA 2027 — Publicación en GitHub Pages

## Archivos que deben quedar en la raíz del repositorio

- `index.html`
- `.nojekyll`
- `assets/logo-capacitacion-canales.png`
- `assets/logo-csb-directo.png`
- `assets/propuesta-1.png`
- `assets/propuesta-2.png`

## Publicar

1. Crea un repositorio de GitHub, por ejemplo `sigca-2027`.
2. Descomprime el ZIP y sube `index.html`, `.nojekyll` y la carpeta `assets` a la **raíz del repositorio**, manteniendo esa estructura. No subas solo el ZIP.
3. Ve a **Settings > Pages > Build and deployment**. Selecciona **Deploy from a branch**, rama `main` y carpeta `/(root)`, y guarda.
4. Cuando termine el despliegue, entra a `https://USUARIO.github.io/sigca-2027/` (sustituye USUARIO y el nombre del repositorio).

**Importante:** la vista de archivos de github.com muestra el código, no ejecuta el dashboard. Hay que abrir la URL de GitHub Pages.

## Datos y seguridad

Los registros de seguimiento se guardan localmente en el navegador (localStorage); no se sincronizan entre usuarios ni equipos. Exporta respaldos JSON regularmente. No subas información personal o confidencial al repositorio público. Para operaciones compartidas se necesitaría almacenamiento centralizado y control de acceso.
