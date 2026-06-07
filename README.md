# ColorBand PWA — Instrucciones de instalación

## 1. Subir a GitHub Pages

1. Ve a **github.com** e inicia sesión (crea cuenta gratis si no tienes)
2. Clic en **New repository**
3. Nombre: `colorband` — márcalo como **Public**
4. Clic **Create repository**
5. Sube estos archivos (drag & drop en la página del repo):
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - carpeta `icons/` con los dos SVG
6. Ve a **Settings → Pages**
7. En "Branch" selecciona `main` → `/root` → **Save**
8. En 2 minutos tu app estará en: `https://TU-USUARIO.github.io/colorband`

## 2. Instalar en iPad

1. Abre Safari en tu iPad
2. Ve a la URL de arriba
3. Toca el botón **Compartir** (cuadrado con flecha arriba)
4. Toca **"Agregar a pantalla de inicio"**
5. Ponle nombre "ColorBand" → **Agregar**

La app aparece en tu pantalla de inicio como cualquier app nativa.
Funciona **sin internet** una vez instalada.

## Estructura de archivos
```
colorband/
├── index.html      ← el juego completo
├── manifest.json   ← config de la PWA
├── sw.js           ← service worker (offline)
└── icons/
    ├── icon-192.svg
    └── icon-512.svg
```
