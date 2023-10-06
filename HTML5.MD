# HTML 5
Lenguaje utilizado para estructurar y dar formato contenido de la World Wide Web (WWW). Es un lenguaje de etiquetas que te permite hacer referencia a todo tipo de información.

Las etiquetas se utilizan para encapsular información y dotarla de mayor entidad. El nombre de la etiqueta hace referencia a la información que va a contener. Las etiquetas también pueden tener atributos.

Las etiquetas HTML tienen una estructura casi siempre igual. Siempre tienen una etiqueta de apertura y una de cierre:
Ejemplo:
     < etiqueta> contenido </ etiqueta>
     < h1> mi primer encabezado < /h1>

CARACTERISTICAS
- Nuevas etiquetas semánticas
        - < header>
        - < footer>
        - < article>
        - < section>
        Todas sirven para definir la estructura y el propósito del contenido
    
- Canvas < canvas> --> sirve para dibujar gráficos y animaciones

- < audio> y < video> --> podemos insertar audios y videos sin nuevos plug ins

- Formularios mejorados
        - < input type "email">
        - < input type "range">
        Permiten crear formularios más sofisticados y fáciles de usar

- Geolocalización: nos permite acceder a la ubicacion del usuario a través del navegador. Esto permite crear aplicaciones más personalizadas y contextuales.

Para inspeccionar aplicaciones web de Chrome se utiliza devTools. Con tener chrome instalado ya tenemos esto.



ESTRUCTURA DEL DOCUMENTO HTML

Lo primero es crear un repositorio nuevo para cada proyecto.
Una vez lo hemos creado en el ordenador, creamos un carpeta dentro del repositorio que va a contener un archivo html. (lo llamamos index.html). Para empezar a escribir codigo, escribimos html y seleccionamos html:5 Todos los ficheros que esten en las carpetas de las sesiones los voy a llamar index.html

<! DOCTYPE html> indica el tipo de documento, en este caso html

< html lang="en"> etiquetas del documento, aqui estará todo mi contenido.

< head> tendremos metadatos. No se ven en el navegador

    < meta charset="UTF-8">
    < meta name="viewport" content="width=device-width, initial-scale=1.0">
    < title>Document </ title> aqui ponemos el nombre del documento (a nivel interno, nadie más que nosotros lo va a ver)

</ head>


< body> aqui dentro estará el contenido que queremos que se pueda visualizar. Con etiquetas, escribimos texto, videos, canvas, etc.

SOY UN COMENTARIO  

</ body>

</ html>


También se pueden hacer comentarios dentro de HTML. Si lo escribimos tal cual sí se verá en la web (ver donde pone SOY UN COMENTARIO). Si queremos que no se vea lo escribimos así:
<! -- SOY UN COMENTARIO --> (ver doc index.html)

a. Doctype nos indica que nuestro doc es de tipo html
b. Etiquetas HTML: tiene dos etiquetas hijas:
    - head (metadatos): elementos que no se ven dentro del navegador
    - body: donde estará el contenido que se podrá visualizar en los navegadores
c. Etiquetas: todas las etiquetas tienen una apertura (< head>) y un cierre (</ head>). Dentro de ellas tenemos el contenido que queremos renderizar.



ETIQUETAS QUE SE USAN EN LA CABECERA (HEAD)
No tienen representación o visualización en el contenido que renderiza el navegador. Son meta-información adicional.

Hay dos grandes tipos:

1. RELACIÓN
2. METADATOS

< head>
    < meta charset="UTF-8">: indicamos que todo lo que yo escriba estara contemplado en UTF-8 (simbolos que necesito para entenderme en la vida normal: letras, comas, etc)

    < meta name="viewport" content="width=device-width, initial-scale=1.0"> control del tamaño y forma de la ventana grafica: la ventana grafica es el area en la que se puede ver el contenido en el navegador.

    < link rel="stylesheet" href="favicon.ico" type="image/x-icon"> paa que en la pestaña de chrome salga un icono nuestro y no la bola del mundo. Para ello crearemos una carpeta que se llame assets donde meteremos imagenes, etc. Se guarda arrastrando hasta la carpeta de assets en vs code.

    < link rel="stylesheet" href="style.css"> es una etiqueta link:css. Un archivo css nos permite aplicar estilos.(ya lo veremos más adelante)

    < script src""></script> para enlazar con un documento js

    < title>Document</title> Titulo de nuestra página (lo que sale en la pestaña del navegador como nombre)

Otros atributos que podemos utilizar en head son:

- Description: el contenido es texto e indica la descripcion de la pagina que aparece en buscadores
- Keywords: el contenido son palabras clave. SOn una lista de palabras clave separadas por coas. Google no la tiene en cuenta.
- author: el contenido es un nombre e indica el nombre del autor de la página
- theme-color: el contenido es color. Color en formato hexadecimal de la barra de navegación del navegador.
- viewport: el contenido son parámetros. Nos indica la región visible del navegador.