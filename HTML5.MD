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
Una vez lo hemos creado en el ordenador, creamos un carpeta dentro del repositorio que va a contener un archivo html. (lo llamamos index.html). Todos los ficheros que esten en las carpetas de las sesiones los voy a llamar index.html

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

