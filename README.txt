INVENTARIO DE VEHÍCULOS - PWA
================================

Archivos:
- index.html: aplicación completa.
- manifest.json: permite instalarla como aplicación web.
- sw.js: permite funcionamiento offline después de la primera carga.
- logo.png: reemplázalo por tu logo, conservando el mismo nombre.
- icon-192.png / icon-512.png: íconos de la aplicación.
- .nojekyll: facilita publicación directa en GitHub Pages.

DATOS
-----
Los vehículos se guardan localmente en IndexedDB dentro del dispositivo/navegador.
La app también tiene:
- Exportar copia: genera un archivo .json.
- Restaurar copia: permite recuperar el inventario desde ese archivo.

IMPORTANTE
----------
No existe una garantía absoluta de que un navegador nunca borre almacenamiento local.
Por eso es recomendable exportar una copia periódicamente y guardarla en iCloud Drive,
Google Drive, OneDrive u otra ubicación segura.

PUBLICAR GRATIS CON GITHUB PAGES
--------------------------------
1. Crea una cuenta en GitHub si no tienes una.
2. Crea un repositorio nuevo, por ejemplo: inventario-autos.
3. Sube TODOS los archivos de esta carpeta a la raíz del repositorio.
4. Abre Settings > Pages.
5. En Build and deployment, selecciona "Deploy from a branch".
6. Selecciona la rama main y la carpeta / (root), y guarda.
7. GitHub mostrará la dirección pública de la aplicación.

INSTALAR EN IPHONE
------------------
1. Abre la dirección publicada usando Safari.
2. Usa Compartir.
3. Selecciona "Añadir a pantalla de inicio".
4. Abre la aplicación desde el nuevo ícono.
5. Registra los vehículos desde la aplicación instalada.
6. Usa "Exportar copia" periódicamente.

CAMBIAR EL LOGO
---------------
Reemplaza logo.png por tu archivo PNG.
Idealmente usa una imagen cuadrada.
Conserva exactamente el nombre: logo.png

SEGURIDAD
---------
El inventario NO está incluido en el repositorio ni en el HTML.
Los datos que agregas se guardan localmente en el dispositivo.
