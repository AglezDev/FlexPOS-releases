# FlexPOS Mobile — Releases de prueba

Releases públicas de FlexPOS Mobile para Android, para que usuarios
probadores descarguen la APK e instalen la app en su teléfono.

## Para probar la app

1. Abre la pestaña **Releases** de este repo.
2. Descarga el archivo `.apk` del release más reciente.
3. En el teléfono, ábrelo e instala (Android pedirá permitir "instalar
   apps desconocidas" para esa descarga; es normal fuera de Play Store).

## Para publicar un release (Arquimedes)

1. Abre el release en borrador (o crea uno nuevo) en la pestaña Releases.
2. Sube la APK como **asset del release** (botón de adjuntar archivos
   del release). NO la subas con `git push`: git rechaza archivos de
   más de 100 MB, y la APK pesa ~90 MB. Como asset del release el
   límite es 2 GB, así que cabe sin problema.
3. Pulsa **Publish release**.

La app es un punto de venta para negocios: vender, cobrar en efectivo,
transferencia o mixto, llevar la caja, controlar inventario, ver
reportes y mandar la factura por WhatsApp.
