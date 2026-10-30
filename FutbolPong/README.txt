FÚTBOL PONG - Proyecto Android

Incluye:
- Modo contra la computadora (CPU).
- Multijugador local en el mismo dispositivo: jugador 1 a la izquierda y jugador 2 a la derecha.
- Controles por deslizamiento táctil.
- Cancha verde, balón, rebotes y porterías centrales pequeñas.
- Gana quien llegue primero a 5 goles.

PARA GENERAR EL APK:
1. Instala Android Studio en una computadora.
2. Abre la carpeta FutbolPong en Android Studio.
3. Espera a que Gradle termine la sincronización.
4. Selecciona Build > Build Bundle(s) / APK(s) > Build APK(s).
5. El APK de prueba aparecerá en app/build/outputs/apk/debug/app-debug.apk.

NOTA:
Este paquete contiene el proyecto fuente listo para abrir y compilar en Android Studio.
No incluye un APK ya compilado. Para compilarlo se necesita Android Studio, el Android SDK
y conexión a internet la primera vez para descargar Gradle y los componentes necesarios.

OPCIÓN SIN ANDROID STUDIO (GitHub Actions):
1. Crea un repositorio en github.com y sube el CONTENIDO de esta carpeta (que README.txt, app/ y .github/ queden en la raíz del repo).
2. Ve a la pestaña "Actions" y espera a que termine "Compilar APK" (unos 3-5 min).
3. Entra a esa ejecución y descarga "FutbolPong-APK" (viene en un .zip con app-debug.apk dentro).
