# Certificado Web

Este repositorio contiene los archivos necesarios para visualizar el certificado en una página web mediante GitHub Pages.

## Estructura
```
/
├─ index.html
└─ index_archivos/
   ├─ image001.png
   └─ image002.png
```

## Publicación en GitHub Pages
1. Subir `index.html` y la carpeta `index_archivos/` al repositorio.
2. Ir a **Settings → Pages**.
3. Seleccionar:
   - Branch: `main`
   - Folder: `/ (root)`
4. Guardar.

La página quedará publicada en:
```
https://<usuario>.github.io/<repositorio>/
```

## Fecha automática
El archivo `index.html` actualiza la fecha diariamente sin necesidad de ajustes adicionales.

## Prueba local
```
python -m http.server 8000
```
Abrir en el navegador:
```
http://localhost:8000
```
