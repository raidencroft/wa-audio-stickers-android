 Stickers con sonido (app para Android)

App personal y no oficial: abre WhatsApp Web en un WebView e inyecta los scripts de la extensión
"Stickers con sonido" de Shirtep (https://github.com/Shirtep/WA-audio-stickers).
Sin relación con WhatsApp ni con Meta. Usa funciones internas de WhatsApp Web que pueden cambiar.

Licencia: PolyForm Noncommercial 1.0.0 (ver LICENSE.md). Solo uso no comercial.
Required Notice: Copyright Shirtep (https://github.com/Shirtep/WA-audio-stickers)

## Compilar el APK (en la PC)
1. Instala Android Studio: https://developer.android.com/studio
2. File > Open > elige la carpeta de este proyecto. Espera a que termine "Gradle sync"
   (descarga cosas la primera vez; acepta instalar el SDK 34 si lo pide).
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Pulsa "locate" en el aviso: el archivo es app/build/outputs/apk/debug/app-debug.apk

## Instalar en el celular
1. Pasa app-debug.apk al teléfono (cable, Drive, etc.).
2. Ábrelo y permite "instalar apps desconocidas" para la app desde la que lo abres.
3. Abre "Stickers con sonido", vincula WhatsApp Web con tu número secundario
   (WhatsApp > Dispositivos vinculados > Vincular con número de teléfono).
4. Toca el botón 🔊 del borde derecho para abrir el panel. Mantenerlo pulsado recarga la página.

## Ajustes
- MainActivity.kt > MODO_ESCRITORIO_AMPLIO: true = como "sitio de escritorio"; false = ancho del celular.

## Limitaciones conocidas (v0.1)
- Los botones de descargar .webp/.ogg del panel no funcionan dentro de la app.
- Necesita un WebView reciente (Android System WebView actualizado en Play Store).
- No se probó contra WhatsApp: es un primer borrador.
