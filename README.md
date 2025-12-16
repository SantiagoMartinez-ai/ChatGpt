# Pirámide 3D interactiva

Aplicación web estática que muestra una pirámide en 3D utilizando Three.js. Puedes rotarla, desplazarla y hacer zoom libremente con el ratón o gestos táctiles.

## Cómo abrir la aplicación
Tienes dos opciones; elige la que prefieras:

1) **Abrir el archivo directamente**
   - Haz doble clic en `index.html` (o ábrelo con tu navegador) desde la carpeta del proyecto. Al ser una app estática, no requiere instalación adicional.

2) **Usar un servidor local** (útil si tu navegador bloquea archivos locales)
   - Abre una terminal en la carpeta del proyecto y ejecuta:
     ```bash
     python -m http.server 8000
     ```
   - En tu navegador visita <http://localhost:8000> y abre `index.html`.

## Controles de la escena
- Arrastra con el botón izquierdo para rotar.
- Botón derecho para desplazar la cámara.
- Rueda del ratón o pellizca en móviles para hacer zoom.

No se necesitan dependencias adicionales: Three.js se carga desde un CDN.

Si la escena no aparece, prueba a abrirla desde un servidor local (opción 2) y asegúrate de que tu navegador tenga WebGL habilitado.
