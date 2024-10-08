# Evaluacion inicial

1. ¿Que es una página web?

-Una página web es un documento digital accesible a través de Internet mediante un navegador web. Puede contener texto, imágenes, videos y otros elementos multimedia.

2. ¿Que es un servidor web?

-Se trata de un software que almacena, procesa y entrega páginas web a los usuarios. Cuando alguien ingresa una URL en su navegador, el servidor web recibe la solicitud, busca el contenido solicitado y lo envía de vuelta al navegador para que el usuario pueda verlo.
   
3. ¿Que son los lenguajes de marcas? ¿Cuantos conoces?

-Un lenguaje de marcas es una forma de codificar un documento mediante el uso de etiquetas que contienen información adicional sobre la estructura y presentación del texto.

| **Nombre** | **Enlace a documentación** |
|:----------:|:--------------------------:|
| HTML ||
| XML |||
| Markdown |||
| RFT |||
   
4. ¿Que es HTML? ¿Sabes como se estructura?

-Es un tipo de lenguaje de marcas utilizado para la creación de páginas web. Se estructura mediante etiquetas que definen elementos de la página, pudiendo crear encabezados, párrafos, enlaces, imagenes, etc. 

El inicio del documento va definido con un <!Doctype html> que declara el tipo del documento y la versión HTML y se finaliza con un </html> para declarar cuando finaliza la codificación html del documento. Dentro encontramos etiquetas que estructuran el codigo como <head> y <body>.
   
**Respuesta.**

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>
```
_Figura 1: Estructura de un código HTML_

5. ¿Que es CSS?

-Es un lenguaje utilizado para describir la presentación de un documento, permitiendo controlar el diseño visual como son los colores, fuentes, etc.

6. ¿Sabes como funciona un navegador web? Describe brevemente el proceso que sigue para visualizar una página web.:
   
-Un navegador web es una aplicación que permite a los usuarios acceder y visualizar contenido en la red. Para ello se envia una url como solicitud desde el navegador, el DNS traduce la url en una dirección IP para encontrar el servidor donde se aloja la web, el navegador envia una solicitud HTTP al servidor para pedir los archivos, el servidor responde con dichos archivos, el navegador interpreta el archivo codificado con un lenguaje de marcas y finalmente se muestra al usuario.