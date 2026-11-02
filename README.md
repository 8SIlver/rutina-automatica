# Rutina en automatico

Herramienta web personal para seguir una rutina diaria: te indica que debes hacer ahora,
cuanto tiempo te queda y como va el balance entre estudio, rutina de salud y descanso.

- Un solo archivo (`index.html`): HTML + CSS + JavaScript, sin dependencias ni servidor.
- Los datos se guardan en el navegador del dispositivo (`localStorage`). No se envia nada a ningun servidor.
- Hace falta hacer respaldos desde "Mi rutina" (copiar texto o descargar archivo) para no perder la rutina
  si se borran los datos del navegador o si se cambia de dispositivo.

## Publicar con GitHub Pages

1. Sube `index.html` y este `README.md` a un repositorio.
2. En GitHub: Settings > Pages > Source: "Deploy from a branch" > rama `main`, carpeta `/ (root)` > Save.
3. La pagina queda en `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`.
