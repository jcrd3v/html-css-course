# Análisis

## Declaración del tipo de documento (`<!DOCTYPE html>`)

Especifica que el documento es HTML5, lo cual es estándar para páginas web modernas.

## Etiqueta `<html lang="en">`

Define el idioma principal del contenido como inglés (`lang="en`). Si el contenido está en español, sería más apropiado usar `lang="es`.

## Sección `<head>`

Contiene información sobre el documento que no se muestra directamente en la página, como metadatos, enlaces a hojas de estilo y otras configuraciones:

- `<meta charset="UTF-8" />`: Define la codificación de caracteres como UTF-8, lo cual es esencial para soportar caracteres especiales como las tildes y la "ñ".
- `<meta name="viewport" content="width=device-width, initial-scale=1.0" />`: Configura la página para que sea responsive, es decir, para que se adapte correctamente a dispositivos móviles. **width=device-width** asegura que el ancho de la página sea igual al del dispositivo, y **initial-scale=1.0** establece el nivel de zoom inicial.

- `<title>`: Define el título de la página como "Mi primer página web".

## Sección `<body>`

Es la sección donde va el contenido visible de la página, como texto, imágenes, enlaces, tablas, etcétera:

- Un encabezado `<h1>` con el texto "Hola mundo!".
- Un párrafo `<p>` que se presenta como una introducción personal.
