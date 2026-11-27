# Terra Vida

**Slogan:** Dos manos, un planeta: cuidarlo está en nuestras manos.

Aplicación educativa de reciclaje y cuidado ambiental con identidad visual azul marino, cian y dorado. Incluye guía de separación, misiones, eco-puntos, progreso local y minijuego.

## Generar el APK desde GitHub en el celular
1. Descarga y descomprime `TerraVida_GitHub.zip`.
2. Sube el contenido de la carpeta al repositorio GitHub: `.github`, `app`, `build.gradle`, `settings.gradle` y `gradle.properties` deben quedar en la raíz.
3. Abre **Actions**.
4. Selecciona **Generar APK Terra Vida** y pulsa **Run workflow** (o espera a que termine el flujo después de subir los archivos).
5. Abre la ejecución con check verde y descarga el artefacto **Terra-Vida-APK**.
6. Descomprime el artefacto: dentro estará `app-debug.apk`.

Este APK es de depuración para pruebas. Para publicar en Google Play se requiere una versión de lanzamiento firmada.
