 Stickers con sonido (app para Android)

App personal y no oficial: abre WhatsApp Web en un WebView e inyecta los scripts de la extensión
"Stickers con sonido" de Shirtep (https://github.com/Shirtep/WA-audio-stickers).
Sin relación con WhatsApp ni con Meta. Usa funciones internas de WhatsApp Web que pueden cambiar con futuras actualizaciones.

Licencia: PolyForm Noncommercial 1.0.0 (ver LICENSE.md). Solo uso no comercial.
Required Notice: Copyright Shirtep (https://github.com/Shirtep/WA-audio-stickers)

## Compilar el APK (en la PC) por ti mismo
1. Instala Android Studio: https://developer.android.com/studio
2. File > Open > elige la carpeta de este proyecto. Espera a que termine "Gradle sync"
   (descarga cosas la primera vez; acepta instalar el SDK 34 si lo pide).
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Pulsa "locate" en el aviso: el archivo es app/build/outputs/apk/debug/app-debug.apk

## Instalar en el celular
1. Pasa app-debug.apk al teléfono (cable, Drive, etc.).
2. Ábrelo y permite "instalar apps desconocidas" para la app desde la que lo abres.
3. Abre "Stickers con sonido", vincula WhatsApp Web con tu número a usar (de preferencia usa el método de vinculación por codigo y no QR ojo es totlamente seguro libre de cualquier mala intencion)
   (WhatsApp > Dispositivos vinculados > Vincular con número de teléfono> Ingresar Codigo). 
4. Toca el botón 🔊 del borde derecho para abrir el panel. Mantenerlo pulsado recarga la página.
5. Abre el chat a mandar los stickers o directamente omite esto y toca el botón 🔊, se despliega el menu y elige entre los 3 apartados de: Video, Imagen + Audio, Video o GIF + Audio.
6. Selecciona tu video, elige el tramo (recorte) puedes usar los botones para precisión.
7. En formato decides si usar Ajustar (bordes transparentes o franjas dependiendo tu clip) o Recortar (Automaticamente lo pone en relacion aspecto 1:1 - Cuadrado). Dale a "Calcular a opciones", cargará y de preferencia selecciona la que tiene una estrella (automáticamente viene seleccionada pero puedes elegir a criterio tuyo).
8. Añade etiqueta de Autoria y un tag para el "Paquete del sticker"
9. Selecciona "Crear Sticker" navega en la opciones y decide si quieres enviar al chat abierto o a ti mismo. Se enviará y listo tu sticker con audio.

## APK "app-debug.apk" listo para instalar (no compilacion requerida)
A manera de evitar el proceso de compilación a quienes no cuenten con el conocimiento o herramientas, en este repositorio esta subido el apk listo para descarga y realizar los pasos anteriores para obtener tus stickers con audio propios!.

## Ajustes
- MainActivity.kt > MODO_ESCRITORIO_AMPLIO: true = como "sitio de escritorio"; false = ancho del celular.

## Limitaciones conocidas (v0.1)
- Los botones de descargar .webp/.ogg del panel no funcionan dentro de la app.
- Necesita un WebView reciente (Android System WebView actualizado en Play Store).
- Probablemente traiga inconvenientes con la visualización en móvil el Web View: Es una primera versión y futuramente mejore para no emplear la vista de Web.   
