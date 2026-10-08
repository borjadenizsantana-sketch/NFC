# Web de tarjetas NFC (GitHub Pages)

## Archivos
- `index.html`: página inicial con enlaces a perfiles.
- `carlos/index.html`: tarjeta de Carlos Acosta.
- `carlos/carlos-acosta.vcf`: contacto descargable.

## Publicar
1. Entra en https://github.com/borjadenizsantana-sketch/nfc
2. Pulsa **Add file** > **Upload files**.
3. Descomprime el ZIP en tu ordenador y arrastra los archivos y la carpeta `carlos` (no arrastres la carpeta contenedora `nfc_github_pages`).
4. Pulsa **Commit changes**.
5. En el repositorio ve a **Settings** > **Pages**.
6. En **Build and deployment**, selecciona **Deploy from a branch**.
7. Elige la rama `main` y la carpeta `/(root)` y pulsa **Save**.

La URL base esperada es:
https://borjadenizsantana-sketch.github.io/nfc/

La tarjeta de Carlos será:
https://borjadenizsantana-sketch.github.io/nfc/carlos/

## Añadir otro perfil
Crea una carpeta nueva en la raíz, por ejemplo `juan`, y dentro coloca un `index.html` con el diseño de `carlos/index.html` adaptando nombre, teléfono y enlaces. Luego añade el enlace al nuevo perfil en el `index.html` principal. Cada NFC debe grabarse con la URL completa de su perfil.

Nota: GitHub Pages puede tardar unos minutos en publicar cambios. Los datos de contacto son públicos; publica únicamente información que tengas permiso para compartir.
