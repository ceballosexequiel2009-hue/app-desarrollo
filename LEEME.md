# Verse: cómo obtener el APK

1. Creá una cuenta gratis en https://github.com y un repositorio nuevo (por ejemplo "verse").
2. Subí TODO el contenido de esta carpeta al repositorio. Importante: tiene que verse la carpeta oculta ".github".
   (En la web: "Add file" > "Upload files" y arrastrá todo. Si no sube ".github", creá el archivo a mano en
   ".github/workflows/build-apk.yml" con el mismo contenido.)
3. Entrá a la pestaña "Actions". El workflow "Build APK" arranca solo (5 a 10 minutos).
4. Cuando termine en verde, abrí la ejecución y bajá "verse-apk" (viene en un ZIP con app-debug.apk).
5. Pasalo a tu Android e instalalo. Tenés que permitir "instalar apps de orígenes desconocidos".

Notas:
- Es un APK de depuración: sirve para instalar en tu celu, no para Play Store.
- Sin internet se usan tipografías del sistema en lugar de las de Google Fonts.
- "Exportar video" abre el menú de compartir de Android para guardarlo o enviarlo.
