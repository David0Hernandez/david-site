# Sitio One-Page para GitHub Pages

## Cómo desplegar
1) Crea una cuenta en GitHub.
2) Crea un repositorio **public** llamado, por ejemplo, `david-site`.
3) Sube `index.html` (este archivo).
4) En el repo: Settings → Pages → Source: **Deploy from a branch**. Branch: `main` (o `master`). Folder: `/root`. Save.
5) Espera unos segundos. La URL aparecerá en la misma sección de Pages (algo como `https://tu-usuario.github.io/david-site/`).

## Personaliza
- Reemplaza las imágenes en `images/*.jpg` o cambia los `src` por URLs reales.
- Cambia los enlaces de Spotify/YouTube/Instagram.
- Cambia el `<title>` y la meta `description` en el `<head>`.

## Notas
- El `background-attachment: fixed` del hero funciona en desktop. En algunos móviles se desactiva por rendimiento (normal).
- Puedes añadir un archivo `CNAME` con tu dominio si más adelante apuntas un dominio propio a GitHub Pages.
