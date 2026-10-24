# BESA · Génesis y Platón

Atlas web en español de Beit Ein Sof Academy. Versión pública **1.4**, del 24 de octubre de 2026. La edición anterior con español y hebreo se identifica como **1.0** y se conserva con la etiqueta `v1.0.0`.

**[Abrir el atlas publicado](https://besa-genesis-y-platon.parcifal.chatgpt.site)**

## Contenido

- Atlas principal de 14 motivos: los 35 versículos bíblicos citados pueden leerse en español (Reina-Valera 1909), hebreo o ambos. Conserva lectores, controles y notas.
- Ampliación independiente de 37 entradas, con lecturas, referencias, búsqueda, comparación, rutas y mapa de relaciones editoriales.
- Textos y recursos históricos incorporados a la edición pública, junto con sus atribuciones.

Los archivos HTML contienen el código editable, los estilos y la aplicación. Esta edición utiliza HTML y JavaScript estáticos; no requiere claves de API, cuenta, base de datos, instalación de paquetes ni compilación.

## Novedades 1.4

- Reunir selecciones del atlas principal y la ampliación en [Mis citas bíblicas](dist/mis-citas.html).
- Ampliar una selección del mismo pasaje e idioma sin duplicar versículos.
- Ordenar y quitar citas con opción de deshacer el último cambio.
- Copiar o descargar un TXT con la bandeja completa, sus textos, referencias, ediciones y fuentes; sin notas personales.
- Recuperar la edición anterior mediante la etiqueta `v1.3.0`.

La bandeja y las selecciones se guardan localmente en el navegador y dominio utilizados. No hay sincronización de cuentas o dispositivos. El TXT permite conservar y compartir las citas; no es una copia de las notas ni un formato de importación de la bandeja. Los enlaces de la 1.3 siguen recuperando selecciones individuales.

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

Los 57 archivos de `dist/` son copias byte por byte de la edición pública revisada. `public-files.sha256` registra sus sumas de comprobación.

La revisión de seguridad previa de la edición 1.6 no identificó vulnerabilidades reportables; no constituye una auditoría nueva de cada actualización. La preparación de esta copia comprobó además la ausencia de patrones conocidos de credenciales, claves privadas, rutas personales y direcciones de acceso con contraseña. Esto no certifica la seguridad de la cuenta de GitHub, del equipo ni de futuros cambios.

Se excluyen el historial de desarrollo, la configuración interna de alojamiento, credenciales, informes internos, notas personales y libros modernos completos utilizados en la investigación.

## Fuentes y derechos

Las referencias y las atribuciones se consultan en `dist/bibliografia.html`, en los lectores y en los metadatos de los textos incorporados. Las comparaciones y los grados de correspondencia deben leerse con las notas críticas y el estado editorial de cada ficha.

No se concede mediante este repositorio una licencia general sobre todos sus contenidos. Los textos, las traducciones y los recursos de terceros conservan sus propios derechos y condiciones de uso. La disponibilidad pública del código no autoriza por sí sola otros usos.
