# solumeg.github.io — IV Encuentro Pedagógico

Sitio web de la memoria narrativa y sistematización del:

**IV Encuentro Pedagógico: Enseñanza, Tecnología y Humanidad en esto de ser instructor(a)**

Servicio Nacional de Aprendizaje — SENA  
Regional Valle  
Equipo regional de formadores de instructores  
2026

## Publicación prevista

Repositorio: `solumeg/solumeg.github.io`

URL esperada:

https://solumeg.github.io/

## Estructura

El sitio es completamente estático (HTML, CSS y JavaScript), no requiere compilación
y está preparado para publicarse directamente desde la raíz de la rama `main`.

Incluye:

- página de inicio narrativa;
- ejes Enseñanza, Tecnología y Humanidad;
- cruces y tensiones;
- sección de Memorias;
- exposición EntreVistas;
- evaluación y voces;
- metodología de la sistematización;
- documento PDF completo descargable.

## GitHub Pages

El archivo `.nojekyll` ya está incluido.

En GitHub:

1. crear el repositorio público `solumeg.github.io`;
2. cargar el contenido de esta carpeta en la raíz del repositorio;
3. ir a **Settings → Pages**;
4. en **Build and deployment**, elegir **Deploy from a branch**;
5. seleccionar `main` y `/ (root)`;
6. guardar.

La URL pública será:

https://solumeg.github.io/

## Actualización del contenido (19 de octubre de 2026)

Esta entrega conserva la arquitectura HTML y la navegación del sitio anterior.
Se actualizó con el documento corregido de las memorias del IV Encuentro
Pedagógico (DOCX y PDF proporcionados para esta revisión):

- Portada actualizada según la primera página del PDF revisado.
- Texto revisado incorporado en los apartados desplegables de los capítulos
  correspondientes, manteniendo los resúmenes editoriales y el recorrido visual.
- Actualización de horizontes, tensiones, fecha y datos del PDF.
- Agenda del evento consultable dentro de la lectura íntegra del capítulo 1.
- PDF de **49 páginas**, idéntico al archivo entregado, disponible desde todos
  los enlaces de descarga existentes en `docs/memoria-iv-encuentro-pedagogico.pdf`.

### Para actualizar el sitio ya publicado

Reemplaza en la **raíz de `main`** el contenido de los archivos de este paquete.
No subas el ZIP sin descomprimir y no coloques una carpeta contenedora por encima
de `index.html`. GitHub Pages publicará los cambios al completar el despliegue.
