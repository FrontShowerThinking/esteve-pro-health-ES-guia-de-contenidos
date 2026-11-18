# Guía de contenidos · ESTEVE Pro Health España (versión protegida)

Esta carpeta es la web que se publica en GitHub Pages. La guía (texto e imágenes) va **cifrada** (AES-256-GCM) dentro de `index.html` y solo se descifra en el navegador al iniciar sesión con un usuario y contraseña válidos. También funciona abriendo `index.html` directamente desde el ordenador.

- `index.html`: pantalla de inicio de sesión con la guía cifrada dentro.
- `fonts/`, `assets/`: fuente y logos (no contienen información del proyecto).

Las contraseñas **no** están en este repositorio. Para cambiar una contraseña, añadir o quitar un usuario o actualizar la guía hay que volver a generar la carpeta con el script de Showerthinking y subirla de nuevo.

## Publicar en GitHub Pages

1. Sube el contenido de esta carpeta a la raíz de la rama `main` del repositorio.
2. En el repositorio: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`** y guarda.
3. En un par de minutos la guía estará en `https://<organizacion>.github.io/<repositorio>/`.
