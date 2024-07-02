
### Ejercicio Práctico: Crear una Página Web Básica

#### **Objetivo del Ejercicio:**
Construir una página web simple utilizando HTML, CSS y JavaScript, y aprender a utilizar las herramientas de desarrollo del navegador.

---

#### **Paso 1: Estructura HTML Básica**
1. **Crear un Archivo HTML:**
   - Abre Visual Studio Code.
   - Crea un nuevo archivo y guárdalo como `index.html`.

2. **Añadir la Estructura Básica:**
   ```html
   <!DOCTYPE html>
   <html lang="es">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Mi Primera Página Web</title>
   </head>
   <body>
       <header>
           <h1>Bienvenido a Mi Página Web</h1>
       </header>
       <main>
           <section>
               <h2>Sobre Mí</h2>
               <p>Hola, soy un estudiante aprendiendo desarrollo web.</p>
           </section>
           <section>
               <h2>Mis Hobbies</h2>
               <ul>
                   <li>Programación</li>
                   <li>Lectura</li>
                   <li>Deportes</li>
               </ul>
           </section>
           <button id="myButton">Haz clic aquí</button>
       </main>
       <footer>
           <p>&copy; 2024 Mi Página Web</p>
       </footer>
   </body>
   </html>
   ```

---

#### **Paso 2: Añadir Estilos CSS**
1. **Crear un Archivo CSS:**
   - En Visual Studio Code, crea un nuevo archivo y guárdalo como `styles.css`.

2. **Vincular el Archivo CSS en HTML:**
   - Añade el siguiente código dentro del `<head>` de `index.html`:
   ```html
   <link rel="stylesheet" href="styles.css">
   ```

3. **Añadir Estilos Básicos:**
   ```css
   body {
       font-family: Arial, sans-serif;
       margin: 0;
       padding: 0;
       background-color: #f4f4f4;
   }

   header {
       background-color: #333;
       color: white;
       padding: 10px 0;
       text-align: center;
   }

   main {
       padding: 20px;
   }

   section {
       margin-bottom: 20px;
   }

   footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px 0;
       position: fixed;
       width: 100%;
       bottom: 0;
   }

   button {
       background-color: #4CAF50;
       color: white;
       border: none;
       padding: 10px 20px;
       cursor: pointer;
   }

   button:hover {
       background-color: #45a049;
   }
   ```

---

#### **Paso 3: Añadir Interactividad con JavaScript**
1. **Crear un Archivo JavaScript:**
   - En Visual Studio Code, crea un nuevo archivo y guárdalo como `script.js`.

2. **Vincular el Archivo JavaScript en HTML:**
   - Añade el siguiente código antes de la etiqueta de cierre `</body>` en `index.html`:
   ```html
   <script src="script.js"></script>
   ```

3. **Añadir Funcionalidad JavaScript:**
   ```javascript
   document.getElementById("myButton").addEventListener("click", function() {
       alert("¡Hola! Has hecho clic en el botón.");
   });
   ```

---

#### **Paso 4: Utilizar el Inspector de Elementos**
1. **Abrir el Inspector de Elementos:**
   - Abre tu página `index.html` en un navegador web (Chrome, Firefox, etc.).
   - Haz clic derecho en cualquier parte de la página y selecciona "Inspeccionar" (o presiona `F12` en tu teclado).

2. **Inspeccionar y Modificar el Contenido:**
   - Utiliza el panel de "Elementos" para ver y modificar el HTML en tiempo real.
   - Utiliza el panel de "Estilos" para ver y modificar los estilos CSS en tiempo real.

---

#### **Paso 5: Guardar y Verificar los Cambios**
1. **Guardar Todos los Archivos:**
   - Asegúrate de guardar los archivos `index.html`, `styles.css` y `script.js`.

2. **Actualizar la Página en el Navegador:**
   - Vuelve al navegador y actualiza la página para ver los cambios reflejados.

---

#### **Conclusión del Ejercicio:**
Los estudiantes habrán creado una página web básica con HTML, estilizada con CSS y con funcionalidad añadida mediante JavaScript. Además, habrán aprendido a utilizar las herramientas de desarrollo del navegador para inspeccionar y modificar el contenido y estilo de la página en tiempo real.

---
