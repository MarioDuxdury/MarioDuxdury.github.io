# Mario Duxdury

Sitio personal de Mario Duxdury: música en vivo y servicios de programación.

## Muestra inicial

La página principal (`index.html`) es la primera muestra publicada. Incluye las secciones de música y programación con enlaces directos de contacto.

## Publicación con GitHub Pages

Este repositorio es el sitio de usuario `MarioDuxdury.github.io`. Para publicar desde la rama `main`:

1. En GitHub, abre **Settings → Pages**.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/(root)`, y guarda.
4. Los cambios enviados a `main` se publican en [https://marioduxdury.github.io](https://marioduxdury.github.io).

La página y sus recursos son estáticos; no requieren instalar dependencias ni ejecutar un paso de compilación.

## Agregar una demo de proyecto

En `index.html`, busca la sección **Muestras de programación**. La tarjeta visible es una plantilla; debajo hay un ejemplo comentado que puedes copiar para cada proyecto y completar con su nombre, descripción y URL pública.

Si la demo vive en otro repositorio, primero publícala por separado y luego usa su URL en el `src` del `iframe` y en el enlace **Abrir demo completa**. La demo debe permitir mostrarse dentro de un `iframe`; si su alojamiento lo bloquea, conserva solo el enlace para abrirla aparte. GitHub Pages publica archivos estáticos y no ejecuta por sí solo un servidor o base de datos. Para proyectos que necesiten backend, ese servicio debe alojarse aparte.
