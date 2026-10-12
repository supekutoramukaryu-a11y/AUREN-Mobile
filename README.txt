AUREN MOBILE v0.1 — Android y iPhone
====================================

QUÉ ES
Una PWA (aplicación web instalable) con interfaz móvil y colores negro/vino/oro. Incluye comandos sencillos por texto, respuestas habladas del navegador, reconocimiento de voz cuando el navegador lo soporta, hora/fecha, accesos a Google/YouTube/WhatsApp y búsqueda web.

IMPORTANTE
- Esta versión no es todavía una IA conversacional conectada a un modelo.
- Para instalar como app y usar el micrófono, publica los archivos en una web con HTTPS. Abrir index.html directamente como archivo suele impedir el micrófono y el funcionamiento PWA.
- El reconocimiento de voz usa la API del navegador. Su compatibilidad depende del navegador/dispositivo y puede enviar audio a un servicio del navegador; no prometemos reconocimiento 100% local.
- iPhone: abrir la web en Safari y usar Compartir > Añadir a pantalla de inicio (si está disponible en la versión de iOS). La captura de voz puede no estar disponible en todos los navegadores iOS.
- Android: abrir en Chrome y usar el menú ⋮ > Instalar aplicación / Añadir a pantalla de inicio.
- Solo abre enlaces y realiza las acciones explícitas incluidas. No puede controlar libremente el sistema, leer otras apps ni cambiar ajustes privados.

CÓMO PROBARLO EN EL ORDENADOR
Puede abrir index.html para probar texto y la interfaz. Para PWA, service worker y micrófono es necesario servir el sitio por HTTPS (o localhost en el propio ordenador).

PUBLICACIÓN GRATUITA (ejemplo con GitHub Pages)
1. Descomprime el ZIP en tu ordenador.
2. Crea un repositorio público en GitHub.
3. Sube al repositorio los archivos de esta carpeta (index.html, manifest.webmanifest, sw.js, icon.svg, icon-192.png, icon-512.png).
4. En el repositorio, Settings > Pages, elige desplegar desde la rama principal (root) y guarda.
5. Cuando GitHub muestre la URL HTTPS, ábrela desde el móvil e instala AUREN siguiendo las indicaciones de arriba.

ARCHIVOS
- index.html: interfaz y comandos.
- manifest.webmanifest: nombre, icono y modo de instalación.
- sw.js: caché básica para visitas posteriores.
- icon.svg: icono de AUREN.
