# ASIX1_M4_UF1-A3_Apuntes

Apuntes de todo el curso de M4 - Disseny XML

## Primer Capítulo: MARKDOWN

Este texto está en *cursiva*.
Este texto está en _cursiva_.
Este texto está en **negrita**.
Este texto está en __negrita__.

Este texto está en **_negrita y cursiva_**.

1. Primera opción de menú.
2. Segunda opción de menú.
3. Tercera opción de menú.

* Primera opción de lista desordenada.
* Segunda opción de lista desordenada.
- Tercera opción de lista desordenada.
    1. Primer submenú.
    2. Segundo submenú.
- Cuarta opción de lista desordenada.
    * Tercer submenú.
    * Cuarto submenú.
+ Quinta opción de lista desordenada.
+ Sexta opción de lista desordenada.

ksdnsldmlksmldslkmkmldskmfmdslkmflkdsmlkfmslkdmlfksmldkfññls,dñlf,ds,f,dsñlf,ñds,f,dsfñsldf,dsñ,fñlds,fñlds,ñlfds,fñd

lñsmdflmdslkfmlkdsmlkfmdslkmflkmdsmfsdflkdsmlkfmsdlkmflkdsmkflmdslkmflkdsmflkmdslkmflkdsmflkmdslkfmlkdsmflkdsmlfmdslkssdf

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

![Esto es una imagen de un planeta](https://github.com/HugoAlda/ASIX1_M4_UF1-A3_Apuntes/blob/main/Escudo%20Bar%C3%A7a.png "Escudo del Barça")

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

    - Titulos.
    - Parrafos.
    - Listas.
    - Tablas.

* Etiquetas Lineales:

    *Todo contenido esta puesto en una misma linea de codigo continuada.*

    - Enlaces.
    - Estilos.
    - Imagen.

* Etiquetas ```HTML```:
    
    - <h1>