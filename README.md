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

## Sitio publicado

El sitio ya está desplegado en Netlify y accesible en:

- https://villacus-web.netlify.app/

[![Netlify Status](https://api.netlify.com/api/v1/badges/ed743bdd-5429-4527-8d8e-0cc3822a27e5/deploy-status)](https://app.netlify.com/projects/villacus-web/deploys)

