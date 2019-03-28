## Trabajo Practico N°1 
###  Introduccion al maquetado

#### Teoria 


1. _¿Qué es un lenguaje de marcado? ¿Cuál es su utilidad? ¿Qué es un tag? ¿Qué es un atributo?_

  
Un lenguaje de marcado es una forma de codificar un documento que, junto con el texto, incorpora etiquetas o marcas que contienen información adicional acerca de la estructura del texto o su presentación.
El marcado se usaba y se usa en la industria editorial y de la comunicación, así como entre autores, editores e impresores.
Una etiqueta (términos a veces reemplazados por tag) es una marca con clase que delimita una región en los lenguajes basados en XML . Las etiquetas (entre otras muchas cosas) le dicen al programa visualizador de páginas web (o navegador) en qué juego de caracteres está la página, de qué tipo es cada uno de los fragmentos de texto que contiene (por ejemplo, encabezamiento, texto normal, etc.), si están alineados a un lado o centrados, en qué tipo de letra está el texto (cursiva, negrita, etc.), si hay tablas, de qué anchura son etc. Dicho de otro modo: los tags dan al navegador las instrucciones necesarias para que presente la página en pantalla.
Los atributos de las etiquetas HTML sirven para definir detalles de comportamiento o presentación de la etiqueta a los que se les coloca. Se escriben dentro de la propia etiqueta con su nombre de atributo y el valor del atributo entre comillas.

2. _¿Cuál es la utilidad de HTML? ¿Qué conjunto mínimo de tags debe contener un documento elaborado en este lenguaje? Describa brevemente su utilidad._

La utilidad de HTML es para crear páginas web, darles estructura y contenido.
El conjunto de tags minimos esta formado por las etiquetas <HTML> </HTML> las cuales rodean a todo el documento.
Dentro de ellas, se pueden identificar dos partes, denominadas encabezado y cuerpo, con diferentes fines:
En el encabezado <HEAD> </HEAD>, se incluye información variada sobre características del documento. Sus contenidos no se presentan directamente en el documento.
En el cuerpo <BODY> </BODY>, está la descripción de los elementos que componen el propio documento, es decir, los datos que se presentarán en la pantalla. <BODY> permite controlar algunos atributos sobre la apariencia global del documento.
Dentro del encabezado existe una única etiqueta de inclusión obligatoria, denominada <TITLE> </TITLE>. La cadena incluida entre las etiquetas especifica el título mostrado en la ventana del cliente Web cuando se accede al documento. También se utiliza como referencia al añadir un bookmark. La cadena no debe contener etiquetas de formato.

3. _¿Cuál es la utilidad e importancia de los enlaces o links entre páginas? ¿Qué significa hipertexto? ¿Un link solo puede apuntar a otra página? ¿Qué importancia tiene esto último?_

La ultilidad de los enlaces entre paginas es referenciar a otros recursos, como pueden ser imagenes u otros documentos HTML.
Hipertexto es una herramienta que permite enlazar y compartir distinta informacion mediante enlaces llamados hipervinculos
Un link puede apuntar a otra pagina o a alguna seccion de la misma, utilizando la etiqueta <a> y dentro haciendo referencia a donde apunta.

4. _¿Qué es el Rendering Engine de un Browser? ¿Cuál es el que utiliza cada uno de los 5 browsers más conocidos (Chrome, Firefox, Safari, IE-Edge, Opera)? ¿Cuál es la importancia de conocer cada uno de ellos en la construcción de un sitio?_

  
