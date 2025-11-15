# Villacus web

Proyecto web estático sencillo que contiene la página principal del sitio de Villacus.

## Descripción

- **Propósito:** Presentar la web estática del proyecto; incluye `index.html`, `style.css` y la carpeta `images`.
- **Tecnologías:** HTML y CSS (sin dependencias de servidor necesarias).

## Estructura del proyecto

- **`index.html`:** Página principal.
- **`style.css`:** Estilos para la página.
- **`images/`:** Imágenes utilizadas en la web.

## Cómo ejecutar localmente

- **Abrir directamente:** En el explorador de archivos, abrir `index.html` con el navegador.
- **Servidor local (recomendado para probar rutas y AJAX):**

```powershell
# Desde la carpeta del proyecto (PowerShell)
python -m http.server 5500
# o si usa `py` en Windows:
py -m http.server 5500

# Luego abrir http://localhost:5500 en el navegador
```

## Desarrollo

- **Editar archivos:** Modifica `index.html` y `style.css` según necesites.
- **Añadir imágenes:** Coloca nuevos archivos en `images/` y actualiza las rutas en `index.html`.

## Despliegue sugerido

- **GitHub Pages:** Subir este repositorio a GitHub y activar Pages desde la rama `main`.
- **Hosting estático:** Netlify, Vercel o cualquier hosting de archivos estáticos funciona bien.

## Sitio publicado

El sitio ya está desplegado en Netlify y accesible en:

- https://villacus-web.netlify.app/

- **Badge de estado (opcional):** Netlify ofrece un badge de estado de despliegue que puedes añadir al `README.md`. Para obtenerlo, ve al panel de tu sitio en Netlify > Site settings > General > Deploy badges o busca "Deploy status badge"; copia el URL del badge y añádelo como imagen Markdown:

```markdown
[![Netlify Status](https://api.netlify.com/api/v1/badges/<YOUR_BADGE_ID>/deploy-status)](https://app.netlify.com/sites/<your-site-name>/deploys)
```

- **Despliegue continuo:** Si quieres que cada push a `main` se despliegue automáticamente, conecta tu repositorio a Netlify desde el panel de Netlify (Site settings > Continuous Deployment) y autoriza GitHub/GitLab/Bitbucket.

## Contribuciones

- **Cómo contribuir:** Abre un issue o un pull request con cambios pequeños. Describe qué cambias y por qué.

## Contacto

- **Autor / Equipo:** Villacus
- **Correo:** (añadir correo o formulario de contacto aquí)

---

Si quieres, puedo añadir una sección de ejemplos, capturas (`images/demo.png`) o instrucciones para automatizar deploy con GitHub Actions.
