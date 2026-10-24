# BESA · Génesis y Platón

Atlas web en español de Beit Ein Sof Academy. Versión pública **1.8**, del 24 de octubre de 2026. La edición anterior con español y hebreo se identifica como **1.0** y se conserva con la etiqueta `v1.0.0`.

**[Abrir el atlas publicado](https://besa-genesis-y-platon.parcifal.chatgpt.site)**

## Contenido

- Atlas principal de 14 motivos: los 35 versículos bíblicos citados pueden leerse en español (Reina-Valera 1909), hebreo o ambos. Conserva lectores, controles y notas.
- Ampliación independiente de 37 entradas, con lecturas, referencias, búsqueda, comparación, rutas y mapa de relaciones editoriales.
- Textos y recursos históricos incorporados a la edición pública, junto con sus atribuciones.

Los archivos HTML contienen el código editable, los estilos y la aplicación. Esta edición utiliza HTML y JavaScript estáticos; no requiere claves de API, cuenta, base de datos, instalación de paquetes ni compilación.

## Novedades 1.8

- Guardar una copia JSON del progreso del recorrido PB26: marcas de lectura y última posición.
- Importar desde un archivo o pegando su contenido, con validación del documento y vista previa antes de incorporar.
- Reunir las marcas de ambas copias sin duplicarlas; conservar la posición actual o retomar la indicada en la copia.
- Cancelar la vista previa o deshacer la última importación antes de continuar el recorrido.
- Recuperar la edición anterior mediante la etiqueta `v1.7.0`.

Abrí «Copia del progreso» desde el recorrido o el panel del documento. La copia admite hasta 16 KB y valida los identificadores de las 15 comparaciones de PB26. Los títulos y textos se recuperan del catálogo del atlas. Se aceptan sólo el formato y los campos del progreso; las notas personales y Mis citas conservan sus propias copias.

El progreso permanece en el navegador y dominio utilizados. El JSON permite trasladarlo manualmente; no hay sincronización de cuentas o dispositivos. La opción de deshacer se conserva hasta que se cambia de paso, se modifica el progreso, se recibe un cambio de otra pestaña o se cierra/recarga la página.

## Recorrido de estudio (desde 1.7)


- [Recorrido de estudio de las 15 comparaciones](dist/lecturas-2026.html?recorrido=1&nota=1#lectura-1): anterior, siguiente y selección directa de nota.
- Marcar comparaciones como leídas y retomar la última consulta. La posición y las marcas se guardan en el navegador y dominio utilizados.
- Consultar las fichas relacionadas y regresar al mismo paso mediante un enlace contextual. Los controles de los lectores y los datos editoriales se conservan.
- Compartir el enlace de una nota sin incluir las marcas de lectura.

La lista completa conserva su búsqueda y sus filtros. El recorrido comprende las 15 comparaciones del documento. Su progreso se guarda por separado de las notas personales y de las copias de Mis citas; no hay sincronización entre navegadores o dispositivos.

## Documento comparativo y citas imprimibles (desde 1.6)


- [Documento comparativo PB26](dist/lecturas-2026.html): 15 notas del PDF aportado «Timeo de Platón y Génesis 1–11», con página del archivo, página interna y valoración atribuida al documento.
- Notas integradas en las 18 fichas relacionadas de la ampliación, en su búsqueda general, filtros y preparación de evidencia. Se conserva el corpus anterior y sus evaluaciones en revisión.
- Contraste de la reseña de Banner, la respuesta de Gmirkin y la reseña de Cook. El argumento ético de Critias y Génesis se mantiene diferenciado del alcance de la calificación del PDF respecto del Timeo.
- [Mis citas bíblicas](dist/mis-citas.html): vista imprimible con título, idiomas, versículos y fuentes; impresión desde el navegador y descarga de un documento HTML autónomo.

Para guardar un PDF, usá «Imprimir / guardar PDF» y elegí el destino en el diálogo del navegador. Si el visor integrado no muestra el diálogo, descargá el documento HTML y abrilo en tu navegador habitual. La generación final del PDF depende de ese navegador y sus opciones de impresión.

Las copias JSON de la 1.5 siguen siendo compatibles. La bandeja y las selecciones se guardan localmente en el navegador y dominio utilizados. Para trasladarlas, descargá la copia JSON y abrila desde «Importar una copia» en el destino. Se admiten 200 KB y 200 selecciones; pasajes, idiomas y versículos se validan contra el catálogo incorporado. El archivo aporta referencias: los textos y enlaces se recuperan del propio atlas.

TXT y HTML son documentos de lectura; JSON es la copia restaurable. Estos formatos de Mis citas excluyen las notas personales. No hay sincronización de cuentas o dispositivos. Los enlaces y controles de las versiones anteriores se conservan.

El PDF aportado se incorpora mediante notas y referencias; el archivo completo y sus imágenes no se incluyen en esta publicación. El documento no identifica a su autor. Sus valoraciones se muestran como posiciones atribuidas y no sustituyen las evaluaciones de las fichas. Las reseñas públicas enlazadas y la respuesta de Gmirkin se contrastaron en esta entrega; las otras referencias del documento no equivalen a una nueva lectura íntegra de esos libros.

## Herramientas de lectura desde 1.1

- Copiar un pasaje o un versículo bíblico con referencia, edición y fuente.
- Descargar el pasaje en TXT, sin notas personales.
- Abrir el español bíblico desde la ampliación sin alterar sus ajustes de lectura.
- [Historial de versiones](dist/versiones.html) y [metadatos de la entrega](dist/release.json).

Los textos y los datos editoriales de los 14 motivos y las 37 fichas se mantienen. Las versiones de archivos y formatos anteriores se conservan por compatibilidad; no representan la nueva numeración pública.

## Usar y alojar

La carpeta `dist/` es la raíz del sitio. El punto de entrada es `dist/index.html`; la ampliación actual es `dist/ampliacion.html`. Para alojarlo, publicar el contenido de `dist/` conservando los nombres y las subcarpetas. Las versiones anteriores se mantienen para conservar enlaces existentes.

El repositorio no configura despliegues automáticos. La publicación actual en GPT Sites se administra por separado.

Las notas, las selecciones guardadas y las preferencias se almacenan en el navegador de cada lector. Al cambiar de dominio, se deben trasladar las notas mediante las funciones de exportación e importación del atlas. Las copias personales pueden contener información privada y no deben incorporarse a Git.

## Procedencia y revisión

Los 67 archivos de `dist/` son copias byte por byte de la edición pública revisada. `public-files.sha256` registra sus sumas de comprobación.

La revisión de seguridad previa de la edición histórica de la ampliación 1.6 (anterior a la numeración pública actual) no identificó vulnerabilidades reportables; no constituye una auditoría nueva de cada actualización. La preparación de esta copia comprobó además la ausencia de patrones conocidos de credenciales, claves privadas, rutas personales y direcciones de acceso con contraseña. Esto no certifica la seguridad de la cuenta de GitHub, del equipo ni de futuros cambios.

Se excluyen el historial de desarrollo, la configuración interna de alojamiento, credenciales, informes internos, notas personales y libros modernos completos utilizados en la investigación.

## Fuentes y derechos

Las referencias y las atribuciones se consultan en `dist/bibliografia.html`, en los lectores y en los metadatos de los textos incorporados. Las comparaciones y los grados de correspondencia deben leerse con las notas críticas y el estado editorial de cada ficha.

No se concede mediante este repositorio una licencia general sobre todos sus contenidos. Los textos, las traducciones y los recursos de terceros conservan sus propios derechos y condiciones de uso. La disponibilidad pública del código no autoriza por sí sola otros usos.
