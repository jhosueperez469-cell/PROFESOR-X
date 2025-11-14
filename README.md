# Certificado Web — GitHub Pages

Este repositorio contiene una versión web del certificado, lista para publicarse mediante **GitHub Pages**.

## 📁 Estructura del proyecto
Asegúrate de mantener esta estructura:

```
/
├─ index.html
└─ index_archivos/
   ├─ image001.png
   └─ image002.png
```

## 🚀 Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube:
   - `index.html`
   - La carpeta `index_archivos/` con las imágenes.
3. Ve a **Settings → Pages**.
4. En **Source**, selecciona:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Guarda.

Después de unos segundos, tu sitio estará disponible en:
```
https://<tu-usuario>.github.io/<nombre-del-repo>/
```

## 📅 Fecha automática
El archivo `index.html` ya incluye un script que actualiza cada día la fecha mostrada en formato:
```
DD/MM/YYYY
```
No requiere modificaciones.

## 🧪 Probar localmente
Si quieres ver la página antes de subirla:

```
python -m http.server 8000
```

Luego abre:

```
http://localhost:8000
```

## ✔️ Listo para usar
Solo sube los archivos al repositorio y activa GitHub Pages. Tu certificado web quedará funcionando automáticamente.
