# hydra-fotos-videos

Imágenes y videos para usar en Hydra, ordenados por carpeta.

Carpetas: plantas, tecnologia, micro-universe, texturas, elementos-adicionales, grupo-2, clase-ejemplo.

Para cargar una imagen en Hydra, copia la ruta del archivo después de `main/`:

```js
s0.initImage("https://raw.githubusercontent.com/saralunarm-cpu/hydra-fotos-videos/main/plantas/plantas-01.jpg")
src(s0).out()
```

Para un video, igual pero con `s0.initVideo(...)`.
