# ASIX1_M4_UF1-A3_Apuntes

Apuntes de todo el curso de M4 - Disseny XML de Hugo Alda Cárdenas

## Primer Capítulo: MARKDOWN

### Formas de darle estilo al texto:

Este texto está en *cursiva*.
Este texto está en *cursiva*.
Este texto está en **negrita**.
Este texto está en **negrita**.

Este texto está en ***negrita y cursiva***.

1. Primera opción de menú.
2. Segunda opción de menú.
3. Tercera opción de menú.

* Primera opción de lista desordenada.
* Segunda opción de lista desordenada.

- Tercera opción de lista desordenada.
    1. Primer submenú.
    2. Segundo submenú.
* Cuarta opción de lista desordenada.
  * Tercer submenú.
  * Cuarto submenú.

```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    </body>
</html>
```

(Sirve para visualizar codigo sin necesidad de ejecutarlo y se vea como tal)

[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

![Esto es una imagen de un planeta](https://github.com/HugoAlda/ASIX1_M4_UF1-A3_Apuntes/blob/main/img/Escudo%20Bar%C3%A7a.png "Escudo del Barça")

|Primera Col|Segunda Col|3 Col|
|----------------|:-------------:|---------------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha| 134€|
|Estilo Cebra|Gris|Blanco|
|Clase|ASIX1|M4|
-[ ] Opción A
-[X] Opción B
-[ ] Opción C

## Segundo Capitulo: Introducción HTML

```
<p>contenido visible</p> - El atributo <p> hace referencia a un parrafo en HTML.

<img href="ruta imagen"> - Dicha imagen se puede encontrar tanto en local como en red. Para buscar la imagen en local siempre partiremos de ./ruta imgagen.

<br> - Se utiliza para hacer saltos de linea en HTML.
```

```
<!DOCTYPE html> <- Indica el tipo de documento y lenguaje que se va a utilizar.
<html lang="en"> <- Indica el principio del contenido de la pagina web, el atributo "lang" hace referencia al idioma en el cual estara todo el contenido (language).
    <head> <- Aqui encontraremos todo lo relacionado con la configuración de la pagina web, en esta todo el contenido que se ponga no sera visible.
        <meta charset="UTF-8"> <- Esta etiqueta se utiliza para especificar el conjunto de caracteres que se utilizará para interpretar y mostrar el contenido de la página.
        <meta name="viewport" content="width=device-width, initial-scale=1.0"> <- Indica el tamaño de la pantalla la cual ocupara dicha paguina.
        <title>Document</title> <- Esta etiqueta define el titulo en la pestaña del navegador de la pagina web.
        <icon>"ruta imagen"</icon> <- En esta etiqueta pondremos la imagen que queremos que se vea en la pestaña del navegador web junto con el titulo.
    </head>
    <body> <- En esa etiqueta pondremos todo el contenido visible de nuestra pagina web.
        
    </body>
</html>
```

* Etiquetas Bloque:
  
    *Tanto el codigo como la etiqueta estan hechos en varios saltos de linea.*

  * Titulos.
  * Parrafos.
  * Listas.
  * Tablas.

* Etiquetas Lineales:

    *Todo contenido esta puesto en una misma linea de codigo continuada.*

  * Enlaces.
  * Estilos.
  * Imagen.

* Etiquetas ```HTML```:

  * ```<h>``` -> Esta etiqueta sirve para añadir encabezados en nuestra pagina web. A dicha etiqueta le varia el tamaño a menor según mas mayor sea el numero introducido. ```<h1>,<h2>,<h3>,<h4>,<h5>,<h6>```. Ej: ```<h1>Encabezado</h1>```.
  * ```<p>``` -> Esta etiqueta sirve para añadir texto en formato de parrafo. Ej: ```<p>Hola me llamo Hugo Alda.</p>```

  * ```<table>``` -> Esta etiqueta sirve para crear tablas.

Ej:

```
<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Tablas</title>
        <style>
            .textoAzul {
                color: blue;
            }
            #textoRojo {
                color: red;
            }
        </style>
    </head>
    <body>
        <table border="2">
            <thead>
                <tr id="textoRojo">
                    <td>Puesto</td>
                    <td>Nombre</td>
                    <td>Tiempo</td>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1r</td>
                    <td>Hugo Alda</td>
                    <td>1:20:56</td>
                </tr>
                <tr class="textoAzul">
                    <td>2nd</td>
                    <td>Roberto Noble</td>
                    <td>1:30:04</td>
                </tr>
            </tbody>
            <tfoot>
                <tr>
                    <td>Puesto</td>
                    <td>Nombre</td>
                    <td>Tiempo</td>
                </tr>
            </tfoot>
        </table>
    </body>
</html>
```

Como se vería:

![Esto es la imagen de la tabla](https://github.com/HugoAlda/ASIX1_M4_UF1-A3_Apuntes/blob/main/img/Tabla.png "Ej Tabla")

## Tercer Capitulo: Responisve

