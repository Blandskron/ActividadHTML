
### Ejercicio Práctico: Exploración de un Documento HTML Completo

#### **Objetivo del Ejercicio:**
Comprender la estructura y los elementos fundamentales de un documento HTML a través de un ejemplo detallado y comentado.

---

#### **Paso 1: Definir el Tipo de Documento**
```html
<!DOCTYPE html> <!-- Define el tipo de documento y la versión de HTML (HTML5 en este caso) -->
<html lang="es"> <!-- Raíz del documento HTML, especifica el idioma del contenido (español) -->
```

---

#### **Paso 2: Configuración del Head del Documento**
```html
<head> <!-- Contiene metadatos/información sobre el documento -->
    <meta charset="UTF-8"> <!-- Establece el juego de caracteres del documento a UTF-8 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Configura la vista para dispositivos móviles y zoom inicial -->
    <title>Documento HTML de Ejemplo</title> <!-- Título del documento, mostrado en la pestaña del navegador -->
</head> <!-- Fin de la sección head -->
```

---

#### **Paso 3: Contenido del Cuerpo del Documento**
```html
<body> <!-- Contiene el contenido visible de la página -->
```

---

#### **Paso 4: Estructura de la Cabecera**
```html
<header> <!-- Cabecera del documento, usualmente contiene elementos introductorios o de navegación -->
    <h1>Bienvenido a mi página HTML de ejemplo</h1> <!-- Encabezado principal de la página -->
    <nav> <!-- Sección de navegación -->
        <ul> <!-- Lista no ordenada para los enlaces de navegación -->
            <li><a href="#texto">Texto</a></li> <!-- Elemento de lista con enlace ancla al texto -->
            <li><a href="#imagenes">Imágenes</a></li> <!-- Elemento de lista con enlace ancla a imágenes -->
            <li><a href="#listas">Listas</a></li> <!-- Elemento de lista con enlace ancla a listas -->
            <li><a href="#tablas">Tablas</a></li> <!-- Elemento de lista con enlace ancla a tablas -->
            <li><a href="#formularios">Formularios</a></li> <!-- Elemento de lista con enlace ancla a formularios -->
        </ul>
    </nav>
</header> <!-- Fin del header -->
```

---

#### **Paso 5: Sección de Texto**
```html
<section id="texto"> <!-- Sección para contenido relacionado con texto, identificado con "texto" -->
    <h2>Texto</h2> <!-- Subtítulo de la sección -->
    <p>Este es un párrafo de ejemplo.</p> <!-- Párrafo de texto -->
    <p><strong>Negrita</strong>, <em>Itálica</em>, <u>Subrayado</u></p> <!-- Párrafo con texto en negrita, itálica y subrayado -->
    <blockquote>Cita de ejemplo en un bloque de cita.</blockquote> <!-- Bloque para citar texto -->
    <pre>Texto preformateado</pre> <!-- Texto preformateado, mantiene espacios y saltos de línea -->
    <code>Código de ejemplo</code> <!-- Utilizado para mostrar una muestra de código -->
</section> <!-- Fin de la sección de texto -->
```

---

#### **Paso 6: Sección de Imágenes**
```html
<section id="imagenes"> <!-- Sección dedicada a imágenes, identificada con "imagenes" -->
    <h2>Imágenes</h2> <!-- Subtítulo de la sección de imágenes -->
    <img src="imagen-ejemplo.jpg" alt="Descripción de la imagen"> <!-- Imagen con su fuente y texto alternativo -->
</section> <!-- Fin de la sección de imágenes -->
```

---

#### **Paso 7: Sección de Listas**
```html
<section id="listas"> <!-- Sección para listas, identificada con "listas" -->
    <h2>Listas</h2> <!-- Subtítulo de la sección de listas -->
    <h3>Lista No Ordenada</h3> <!-- Sub-subtítulo para la lista no ordenada -->
    <ul> <!-- Inicio de una lista no ordenada -->
        <li>Elemento 1</li> <!-- Elemento individual de la lista -->
        <li>Elemento 2</li> <!-- Otro elemento de la lista -->
        <li>Elemento 3</li> <!-- Tercer elemento de la lista -->
    </ul> <!-- Fin de la lista no ordenada -->
    <h3>Lista Ordenada</h3> <!-- Sub-subtítulo para la lista ordenada -->
    <ol> <!-- Inicio de una lista ordenada -->
        <li>Primer Elemento</li> <!-- Primer elemento de la lista ordenada -->
        <li>Segundo Elemento</li> <!-- Segundo elemento de la lista ordenada -->
        <li>Tercer Elemento</li> <!-- Tercer elemento de la lista ordenada -->
    </ol> <!-- Fin de la lista ordenada -->
</section> <!-- Fin de la sección de listas -->
```

---

#### **Paso 8: Sección de Tablas**
```html
<section id="tablas"> <!-- Sección para tablas, identificada con "tablas" -->
    <h2>Tablas</h2> <!-- Subtítulo de la sección de tablas -->
    <table border="1"> <!-- Inicio de la tabla con borde -->
        <tr> <!-- Inicio de la fila de la tabla -->
            <th>Encabezado 1</th> <!-- Celda de encabezado de la tabla -->
            <th>Encabezado 2</th> <!-- Otra celda de encabezado de la tabla -->
        </tr> <!-- Fin de la fila de encabezado -->
        <tr> <!-- Inicio de otra fila de la tabla -->
            <td>Dato 1</td> <!-- Celda de datos de la tabla -->
            <td>Dato 2</td> <!-- Otra celda de datos de la tabla -->
        </tr> <!-- Fin de la fila de datos -->
    </table> <!-- Fin de la tabla -->
</section> <!-- Fin de la sección de tablas -->
```

---

#### **Paso 9: Sección de Formularios**
```html
<section id="formularios"> <!-- Sección para formularios, identificada con "formularios" -->
    <h2>Formularios</h2> <!-- Subtítulo de la sección de formularios -->
    <form action="#"> <!-- Inicio del formulario, "action" define a dónde se enviarán los datos del formulario -->
        <label for="nombre">Nombre:</label> <!-- Etiqueta para el campo de nombre -->
        <input type="text" id="nombre" name="nombre"><br> <!-- Campo de entrada de texto para el nombre -->
        <input type="submit" value="Enviar"> <!-- Botón para enviar el formulario -->
    </form> <!-- Fin del formulario -->
</section> <!-- Fin de la sección de formularios -->
```

---

#### **Paso 10: Pie de Página**
```html
<footer> <!-- Pie de página del documento -->
    <p>Este es el pie de página</p> <!-- Párrafo en el pie de página -->
</footer> <!-- Fin del pie de página -->
</body> <!-- Fin del cuerpo del documento -->
</html> <!-- Fin del documento HTML -->
```

---

#### **Conclusión del Ejercicio:**
Este ejercicio guía a los estudiantes a través de un documento HTML completo y comentado, proporcionando una comprensión detallada de cada parte del documento y su función específica en la estructura de una página web.

---

Este ejercicio práctico proporciona una base sólida para entender la estructura y los elementos fundamentales de un documento HTML, preparando a los estudiantes para crear y personalizar sus propias páginas web.
