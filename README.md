# Radios libres España

Web estática lista para publicar gratis en GitHub Pages.

## Qué hace
- Reproductor de radios españolas para móvil, iPad y escritorio
- Favoritas y buscador
- Controles multimedia
- Instalación como app en navegadores compatibles
- Publicación gratis con GitHub Pages

## Qué he dejado preparado
- Instalación como app en móvil, iPad y PC
- Iconos nuevos estilo radio vintage
- Eliminados los iconos/siglas dentro de cada emisora
- Eliminado el texto secundario bajo cada emisora
- Eliminado el bloque informativo largo
- Sin perder reproducción, favoritos, filtros, búsqueda, volumen, tema ni atajos multimedia

## Lo imprescindible para publicarla gratis
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
- `favicon.ico` -> favicon de la web
- `assets/icons/` -> iconos PNG y SVG de la app

## Notas de instalación
- **PC**: Chrome, Edge y otros navegadores compatibles mostrarán la opción de instalar.
- **Android**: compatible con instalación PWA en navegadores compatibles.
- **iPad / iPhone**: se puede añadir a pantalla de inicio desde Safari. iOS usa especialmente `apple-touch-icon`, por eso ya va incluido.

## Mantenimiento mínimo
Si alguna radio deja de sonar:
- abre `index.html`
- busca `const stations = [`
- cambia la URL dentro de `streams`

## Coste
Todo este flujo puede hacerse gratis usando:
- GitHub Free
- GitHub Pages

## Subida rápida a GitHub Pages
1. Sube el contenido de esta carpeta a la raíz del repositorio.
2. Mantén `index.html`, `manifest.webmanifest`, `sw.js`, `favicon.ico` y `assets/` en la raíz/estructura original.
3. En GitHub: **Settings > Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona tu rama principal y la carpeta **/root**.
6. Guarda y espera a que GitHub publique la web.
