# Publicación en GitHub Pages

## Repositorio

Usuario: `solumeg`  
Repositorio: `solumeg.github.io`

## Opción A — interfaz web de GitHub

1. Inicia sesión en https://github.com
2. Crea un repositorio nuevo:
   - nombre: `solumeg.github.io`
   - visibilidad: **Public**
3. En el repositorio, elige **Add file → Upload files**.
4. Sube **el contenido** de esta carpeta (no la carpeta contenedora).
5. Confirma con **Commit changes**.
6. Abre **Settings → Pages**.
7. En **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
8. Guarda.

La dirección esperada será:

https://solumeg.github.io/

## Opción B — línea de comandos

Desde dentro de esta carpeta:

```bash
git init
git config user.name "solumeg"
git config user.email "solumeg@gmail.com"
git add .
git commit -m "Publicación inicial del IV Encuentro Pedagógico"
git branch -M main
git remote add origin https://github.com/solumeg/solumeg.github.io.git
git push -u origin main
```

Después, si GitHub Pages no se activa automáticamente:

Settings → Pages → Deploy from a branch → main → / (root)

## Nota

No compartas tu contraseña ni un token de acceso en el chat.

## Actualización de un repositorio existente

Si el sitio `https://solumeg.github.io/` ya está publicado, **no es necesario
crear otro repositorio**. Descomprime el ZIP, reemplaza los archivos modificados
en la raíz de `solumeg.github.io` y confirma los cambios en la rama que publica
GitHub Pages. En particular, reemplaza también:

- `docs/memoria-iv-encuentro-pedagogico.pdf` (PDF corregido);
- `assets/portada-iv-encuentro.png` (portada de la versión corregida);
- `styles.css` y las páginas HTML actualizadas.

Cuando termine el despliegue, comprueba el botón «Descargar memoria (PDF)»
y la versión de 49 páginas del documento.
