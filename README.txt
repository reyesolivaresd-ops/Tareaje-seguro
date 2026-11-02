TARE AJE SEGURO - PROYECTO ANDROID

Este proyecto envuelve el HTML actual en una aplicación Android nativa mediante WebView.

PARA GENERAR EL APK:
1. Instala Android Studio en una computadora.
2. Descomprime TareajeSeguroAndroid.zip.
3. En Android Studio selecciona Open y abre la carpeta TareajeSeguroAndroid.
4. Espera a que Gradle sincronice y acepte instalar Android SDK Platform 35 y Build Tools si lo solicita.
5. Selecciona Build > Build Bundle(s) / APK(s) > Build APK(s).
6. El APK se encontrará en app/build/outputs/apk/debug/app-debug.apk.

NOTAS IMPORTANTES:
- Este entorno no tiene Android SDK ni Gradle instalado, por eso no se ha podido compilar ni verificar un APK instalable aquí.
- El HTML se incluye como app/src/main/assets/index.html.
- Los datos y la persistencia dependen de las funciones implementadas en ese HTML. Este envoltorio WebView no agrega por sí solo sincronización en la nube, autenticación real con Gmail ni copias de seguridad.
