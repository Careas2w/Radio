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
