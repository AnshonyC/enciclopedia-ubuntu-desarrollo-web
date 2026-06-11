# Enciclopedia Ubuntu y Desarrollo Web

Guía local para aprender Linux/Ubuntu, terminal, Git, SSH, Apache, PHP puro, `.htaccess`, MariaDB y servidor web local desde cero.

Este proyecto nació como una enciclopedia personal para esos momentos donde toca empezar otra vez: una computadora nueva, un SSD vacío, una instalación limpia de Linux o una configuración perdida. Lo comparto públicamente por si también le sirve a otras personas que están comenzando en Linux y desarrollo web.

## ¿Para quién es?

Este manual está pensado para personas que quieren aprender desde abajo, pieza por pieza.

El enfoque principal es el desarrollo web con **PHP puro**, también llamado PHP vanilla o desarrollo sin framework. Es decir: crear manualmente archivos como `index.php`, organizar carpetas propias, configurar `.htaccess`, conectar PHP con MariaDB/MySQL, manejar rutas, permisos, Apache, Git, SSH y todo lo necesario para levantar un proyecto web sin depender obligatoriamente de Laravel, Symfony u otros frameworks.

No significa que los frameworks sean malos. Simplemente este manual busca entender primero las bases: cómo funciona un servidor local, cómo se conecta una base de datos, cómo se organiza una app manualmente, cómo se configuran rutas y cómo se trabaja con archivos reales del proyecto.

Si usas Laravel u otro framework, algunas secciones también pueden servirte, especialmente las de Linux, terminal, Git, SSH, Apache, MariaDB y servidor local. Pero el corazón del manual está pensado para quienes quieren aprender desde cero y trabajar de forma más artesanal.

## ¿Qué incluye?

- Primeros pasos después de instalar Ubuntu/Kubuntu.
- Comandos básicos de terminal.
- Manejo de carpetas, rutas y permisos.
- Instalación de programas.
- Git y GitHub.
- SSH y llaves.
- Apache.
- PHP puro.
- `.htaccess`.
- MariaDB/MySQL.
- Servidor web local.
- Dominios locales.
- Conceptos básicos para montar un entorno de desarrollo.
- Recomendaciones de seguridad.
- Solución de problemas comunes.

## ¿Cómo se usa?

1. Descarga o clona este repositorio.
2. Abre el archivo `index.html` en tu navegador.
3. Lee la advertencia inicial.
4. Crea una clave maestra si usarás el autoguardado.
5. Llena tus rutas y datos locales.
6. Copia los comandos según lo que estés configurando.

El manual está pensado para usarse mientras haces las cosas, no solo para leerlo como documento.

## Sobre el autoguardado cifrado

El manual puede guardar datos de configuración, como rutas locales, nombre de proyecto, dominio local o datos de base de datos.

La idea es evitar tener que rellenar todo cada vez que se abre el archivo.

Los datos se guardan cifrados en el almacenamiento interno del navegador. La clave maestra no se guarda. Esa clave se usa para cifrar y descifrar la información local.

Importante:

- No subas datos reales, contraseñas, rutas privadas o archivos generados con información personal al repositorio.
- Si borras los datos del navegador, puedes perder la información guardada.
- Si abres el HTML en otro navegador o computadora, los datos anteriores no estarán disponibles.
- Este proyecto está pensado para uso local.

## Seguridad

Este manual puede ayudarte a generar comandos, pero debes revisar antes de ejecutar cualquier cosa que modifique archivos, permisos, discos, servicios, base de datos o configuración del sistema.

Ten especial cuidado con comandos que usen:

- `sudo`
- `rm`
- `chmod`
- `chown`
- `mkfs`
- `dd`
- configuración de Apache
- configuración de MariaDB
- llaves SSH
- archivos de contraseñas

No ejecutes comandos que no entiendas todavía. Lee la explicación, revisa la ruta y, si hay duda, prueba primero en una carpeta de práctica.

## ¿Puedo sugerir mejoras?

Sí. Puedes abrir un Issue con:

- Errores encontrados.
- Comandos que no funcionaron.
- Explicaciones confusas.
- Ideas de nuevas secciones.
- Mejoras visuales.
- Recomendaciones para otras distribuciones Linux.

También puedes hacer un fork y enviar un Pull Request.

## Aviso sobre IA

Este proyecto fue creado y ampliado con ayuda de inteligencia artificial. Aunque se revisó con cuidado, puede contener errores, comandos incompletos, casos no cubiertos o recomendaciones que necesiten ajuste según la versión de Linux, la distribución o el entorno de cada persona.

Se agradecen comentarios, pruebas y correcciones de la comunidad.

## Estado del proyecto

En desarrollo constante.

La meta es que esta guía sea cada vez más clara, segura, compacta y útil para personas que están empezando en Linux/Ubuntu/Kubuntu y desarrollo web local con PHP puro.

## Licencia

Este proyecto usa licencia MIT. Puedes usarlo, copiarlo, modificarlo y compartirlo, manteniendo el aviso de licencia.
