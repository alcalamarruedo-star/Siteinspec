SiteInspect 1.0 — instalación GitHub Pages
1. Crear repositorio público nuevo siteinspect-v1 con README.
2. Extraer ZIP y subir los archivos de la raíz (index.html, app.js, word.js, sw.js, manifest.json, iconos).
3. Subir también .github/workflows/pages.yml. Si el navegador omite la carpeta oculta, crear el archivo con Add file > Create new file y pegar el contenido del pages.yml incluido.
4. Settings > Pages > Source > GitHub Actions.
5. Actions > Publish SiteInspect > Run workflow > main. Esperar resultado verde.
6. Abrir la URL de Pages en Chrome Android e instalar desde menú.
La acción descarga PDF.js automáticamente al publicar; no hay que descargar bibliotecas manualmente. Requiere conexión durante publicación e instalación inicial. Probar PDF, cámara, exportación y modo avión antes de usar datos reales. Guardar copias JSON. Los datos de un sitio anterior no migran automáticamente.
Interfaz en inglés; plantilla Word genérica. Sin pruebas físicas Android ni publicación real realizadas aquí. No subir datos de empresa al repositorio público.
PUBLICAR.txt contiene una copia del workflow para facilitar su creación desde el navegador. No es necesario publicarlo como archivo de la web.
La biblioteca PDF.js no está físicamente en el ZIP: GitHub Actions la incorpora automáticamente al sitio publicado. Si falla la descarga, la publicación falla en vez de distribuir una versión incompleta.
