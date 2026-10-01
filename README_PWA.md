# Mi Cuenta Personal - Royen VIP (PWA)

Esta versión conserva el proyecto original HTML/CSS/JavaScript y añade:
- instalación como aplicación en Android;
- iconos de aplicación;
- manifest.json;
- Service Worker para caché y uso offline después de la primera carga;
- almacenamiento local del proyecto (localStorage).

## IMPORTANTE
Para instalarla como PWA en Android, el proyecto debe abrirse desde HTTPS
(o desde localhost durante pruebas). No basta con abrir index.html directamente
como archivo.

### Forma recomendada
1. Sube la carpeta `MiCuentaPersonal` a un hosting estático con HTTPS.
2. Abre la dirección desde Chrome en tu celular.
3. En Chrome selecciona "Instalar aplicación" o "Añadir a pantalla de inicio".
4. La aplicación aparecerá con el icono de Mi Cuenta.

### Datos
El proyecto utiliza localStorage. Los datos quedan guardados en el navegador
del dispositivo donde uses la aplicación. Esta PWA no agrega una base de datos
ni sincronización entre dispositivos.

## Estructura añadida
- manifest.json
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png
