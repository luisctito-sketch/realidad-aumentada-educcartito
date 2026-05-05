# Realidad Aumentada Educcartito STEAMLab

Esta carpeta contiene la base lista para publicar una experiencia de realidad aumentada en GitHub Pages. La experiencia reconoce una tarjeta de Educcartito y muestra encima un video de Educcartito bailando.

## Archivos incluidos

- `index.html`: página principal de realidad aumentada.
- `.nojekyll`: archivo vacío necesario para evitar problemas con GitHub Pages.
- `marcador-educcartito-steamlab.png`: imagen corregida de la tarjeta.
- `marcador-educcartito-steamlab.jpg`: versión JPG de la misma imagen para imprimir o usar en el compilador de MindAR.
- `INSTRUCCIONES-PASO-A-PASO.txt`: guía rápida para completar el proyecto.

## Archivos que todavía debes agregar

Debes agregar estos dos archivos en la misma carpeta donde está `index.html`:

1. `targets.mind`
2. `educcartito-bailando.mp4`

## Cómo crear `targets.mind`

1. Entra al compilador de imágenes de MindAR.
2. Sube `marcador-educcartito-steamlab.jpg` o `marcador-educcartito-steamlab.png`.
3. Presiona `Start`.
4. Descarga el archivo generado.
5. Renómbralo exactamente como `targets.mind`.
6. Súbelo a esta carpeta.

## Cómo agregar el video

1. Toma el video de Educcartito bailando.
2. Convierte o guarda el video en formato MP4.
3. Renómbralo exactamente como `educcartito-bailando.mp4`.
4. Súbelo a esta carpeta.

## Publicación en GitHub Pages

1. Crea un repositorio llamado `realidad-aumentada-educcartito`.
2. Sube todos los archivos de esta carpeta.
3. En GitHub, entra a `Settings`.
4. Entra a `Pages`.
5. En `Build and deployment`, elige `Deploy from a branch`.
6. Elige la rama `main` y la carpeta `/root`.
7. Guarda.
8. Espera unos minutos.
9. Abre el enlace publicado desde tu celular.

## Prueba final

1. Abre el enlace de GitHub Pages en el celular.
2. Presiona `Iniciar experiencia AR`.
3. Permite el uso de la cámara.
4. Apunta hacia la tarjeta impresa o hacia la imagen en otra pantalla.
5. Educcartito debe aparecer bailando en realidad aumentada.
