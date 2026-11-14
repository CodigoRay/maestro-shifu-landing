# Maestro Shifu — landing de video

Landing estática en HTML, CSS y JavaScript. No requiere Node.js ni proceso de build.

## Archivos
- `index.html`: página principal.
- `media/video.mp4`: video de presentación incluido.

## Publicación
Conecta este repositorio desde Hostinger, selecciona la rama `main` y configura el directorio de despliegue según tu instalación. Si Hostinger publica desde la raíz del repositorio, el archivo `index.html` debe quedar en esa raíz.

## Video
La página reproduce `media/video.mp4`. El video está codificado en MP4/H.264 con audio AAC para mejorar la compatibilidad entre navegadores.

## Redirección
Cuando el video termina, la página espera 900 ms y redirige a:

`https://uplcm.com/4/10118997`

La reproducción automática se intenta en silencio para mejorar la compatibilidad del navegador. El visitante puede activar el sonido manualmente. Algunos navegadores pueden exigir una acción del usuario para iniciar la reproducción.
