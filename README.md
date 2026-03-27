# Radios libres España

Web estática lista para publicar gratis en GitHub Pages.

## Qué hace
- Reproductor de radios españolas para móvil y escritorio
- Favoritas y buscador
- Controles multimedia
- Instalación como app en móviles compatibles
- Publicación gratis con GitHub Pages

## Lo único imprescindible que tienes que hacer tú
1. Crear una cuenta gratuita en GitHub
2. Crear un repositorio público nuevo
3. Subir el contenido de esta carpeta
4. Activar GitHub Pages en:
   - Settings
   - Pages
   - Build and deployment
   - Source: Deploy from a branch
   - Branch: main /(root)

## URL final
Si el repositorio se llama `tuusuario.github.io`, la web quedará en:
`https://tuusuario.github.io/`

Si el repositorio tiene otro nombre, quedará en:
`https://tuusuario.github.io/nombre-del-repo/`

## Archivos
- `index.html` -> la web completa
- `.nojekyll` -> evita procesado innecesario
- `manifest.webmanifest` -> instalación como app
- `sw.js` -> caché básica offline

## Mantenimiento mínimo
Si alguna radio deja de sonar:
- abre `index.html`
- busca `const stations = [`
- cambia la URL dentro de `streams`

## Coste
Todo este flujo puede hacerse gratis usando:
- GitHub Free
- GitHub Pages


## Cambios incluidos en este paquete

- Optimización visual para móvil
- Tema día/noche con botón emoji y persistencia
- Pestaña de favoritas ⭐ delante de “Todas”
- Las favoritas se guardan en el navegador
- Eliminadas las etiquetas redundantes de categoría en cada emisora
- Eliminado el texto secundario de cabecera
- Eliminado el botón aleatorio

## Subida rápida a GitHub Pages

1. Sube el contenido de esta carpeta a la raíz del repositorio.
2. Mantén `index.html`, `manifest.webmanifest` y `sw.js` en la raíz.
3. En GitHub: **Settings > Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona tu rama principal y la carpeta **/root**.
6. Guarda y espera a que GitHub publique la web.
