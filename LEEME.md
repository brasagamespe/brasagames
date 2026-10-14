# Web de Brasa Games en GitHub Pages

Sirve para dos cosas:
1. **`app-ads.txt`**: AdMob lo pide en la raíz de tu web para confirmar que
   los anuncios del juego son tuyos (sin él, los anunciantes pagan menos).
2. **Sitio web de la ficha de Play** y una copia de la política de privacidad.

## Archivos (súbelos TAL CUAL, sin carpetas)

| Archivo | Qué es |
|---|---|
| `index.html` | La portada (Last Ember, enlace a Google Play, privacidad y contacto). |
| `privacidad.html` | La política de privacidad (copia de `docs/politica-privacidad.html`). |
| `app-ads.txt` | `google.com, pub-6497146640608915, DIRECT, f08c47fec0942fa0` |
| `icono.png` | El icono del juego. |

## Pasos

1. Crea una cuenta en **github.com** (gratis). El nombre de usuario será la
   dirección de la web: si eliges `brasagames`, la web será
   `https://brasagames.github.io`.
2. Arriba a la derecha, **+ → New repository**.
   - **Repository name:** exactamente `TUUSUARIO.github.io` (por ejemplo
     `brasagames.github.io`). Es lo que hace que la web quede en la raíz,
     que es donde AdMob busca `app-ads.txt`.
   - **Public**. Pulsa **Create repository**.
3. En el repositorio vacío: **uploading an existing file** (o *Add file →
   Upload files*). Arrastra los 4 archivos de esta carpeta (no la carpeta) y
   pulsa **Commit changes**.
4. **Settings → Pages**: en *Branch* elige `main` y `/ (root)`, **Save**. En uno
   o dos minutos la web está en `https://TUUSUARIO.github.io`.
5. Comprueba en el navegador:
   - `https://TUUSUARIO.github.io` → la portada.
   - `https://TUUSUARIO.github.io/app-ads.txt` → la línea de `google.com, pub-…`.
6. **Play Console → Last Ember → Configuración de la tienda → Datos de contacto
   → Sitio web**: pon `https://TUUSUARIO.github.io` y guarda.
7. Avisa a Claude: revisa en AdMob que lo encuentra (AdMob tarda hasta 24 h en
   volver a mirar).

## Si cambias algo

Edita el archivo aquí y vuelve a subirlo al repositorio (se sobrescribe). Si
cambia la política de privacidad, copia de nuevo `docs/politica-privacidad.html`
como `privacidad.html`.
