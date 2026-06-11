# Cómo funciona el guardado local cifrado

Este manual está diseñado para funcionar como un solo archivo HTML local.

El objetivo es que puedas escribir tus datos de configuración una vez y recuperarlos al volver a abrir el manual, sin tener que llenar todo desde cero.

## ¿Dónde se guardan los datos?

Los datos se guardan dentro del almacenamiento interno del navegador.

No se guardan directamente dentro del archivo HTML.

No se suben a internet.

No se envían al repositorio.

No se comparten con GitHub.

## ¿Por qué no se crea un JSON automáticamente al lado del HTML?

Los navegadores bloquean que un archivo HTML abierto con `file://` pueda crear o modificar archivos libremente en tu computadora.

Eso existe por seguridad. Si un HTML pudiera crear, editar o borrar archivos sin permiso, cualquier archivo descargado podría dañar documentos personales.

Por eso, la versión simple usa almacenamiento local cifrado del navegador.

## ¿Cómo funciona el cifrado?

Cuando escribes una clave maestra, el manual usa esa clave para generar una llave criptográfica temporal.

Esa llave sirve para cifrar y descifrar tus datos.

La clave maestra no se guarda.

Si escribes la clave correcta, los datos se descifran y aparecen.

Si escribes una clave incorrecta, los datos no se pueden leer.

## ¿Una clave diferente carga otra información?

No.

La idea correcta es que exista una sola bóveda local.

La clave correcta abre esa bóveda.

Una clave incorrecta simplemente falla.

## ¿Qué pasa si borro los datos del navegador?

Puedes perder los datos guardados.

Esto puede pasar si limpias almacenamiento del navegador, usas otro navegador, cambias de perfil o abres el archivo en otra computadora.

## ¿Debo guardar contraseñas reales aquí?

Lo más recomendable es no guardar contraseñas reales importantes.

Aunque los datos estén cifrados, este manual está pensado como ayuda local de aprendizaje y configuración, no como administrador profesional de contraseñas.

Para contraseñas reales importantes, usa un gestor de contraseñas dedicado.

## Recomendación

Usa el autoguardado para rutas, nombres de proyecto, dominios locales, usuarios de prueba y datos de laboratorio.

Evita guardar credenciales reales de producción.
