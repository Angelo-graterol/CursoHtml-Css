# Curso HTML + CSS
---
## HTML Básico:

### 1. Estructura de una Etiqueta

< tag>contenido</ tag>

### 2. Parrafos y Encabezados

<p> parrafo </p>

<h1>Titulo</h1>

<h2>Titulo</h2>

<h3>Titulo</h3>

<h4>Titulo</h4>

<h5>Titulo</h5>

<h6>Titulo</h6>

<h6>Titulo</h6>

### 3. Listas

- Ordenadas
  <ol>
    <li></li>
    <li></li>
    <li></li>
  </ol>

- Desordendas
  <ul>
    <li></li>
    <li></li>
    <li></li>
  </ul>


### 4. Enlaces

<a href="https://youtube.com">Enlace</a>

### **¿Cómo hacer que el enlace se abra en otra página?**

Modificando el atributo ***"target"***; para esta hay dos
principales valores: 
- "_self" hace que se abra en la misma página
- "_blank" hace que se abra en otra página

<a href="https://youtube.com" target="blank">Enlace con blank</a>


#### - Atributo "title"
sirve para dar informacion del atributo dentros de la página, sirve para practicamente cualquier etiqueta html, se evidencia al pasar el cursor sobre el elemento

<a href="https://youtube.com" title="enlace a red social">Enlace con title</a>



### 5. Imagenes

<img src="angelo.jpg">

- ### ¿Que sucede si no carga la imagen?
  para cuando la ruta de la imagen no funciona, es importante agregar al atributo "**alt**", que sirve para dar una informacion de lo que representa la imagen

  <img src="angel.jpg" alt="Foto de Angelo">



### 6. Rutas
- Ruta absoluta
  como las que estan en la web, como el enlace a youtube "https://youtube.com"

- Ruta Relativa
  Depende de la ubicacion del arcchivo, hay varias posiblidades
  - El archivo está en la misma carpteta
    
    en este caso se usa el nombre del archivo tal cual, ejemplo "angelo.png"
  - El Archivo está en una carpeta adentro de la carpete donde estamos
    
    en este caso hay que escribir el nombre de la carpeta donde se encuentra antes del nombre del archivo, ejemplo "**imagenes/angelo.jpg**", si se encuentra dentro de otra carpeta dentro de la carpeta imagenes se hace practicamen lo mismo nuevamente, ejemplo "**imagenes/otracarpeta/angelo.png**"
  - El archivo se encuentra una carpeta afuera 

      En este caso se usa "**../**" para acceder a los acrchivo una carpeta afuera del archivo donde estamos, y así sucesivamente si es necesario, ejemplo "**../Repositorios/imagen.png**"

### 7. Formularios
Los formularios permiten obtener datos del usuario
<form>
  <input type="text" placeholder="campo de texto" name="texto" >
</form>

Los ***input*** son los elementos del formulario, trae en sí varios atributos importantes en el funcionamiento del input

- type
    --
  - text
  - number
  - color
  - date
  - file
  - password
  - submit
  - email
  ...

- Placeholder
  --
  funciona para agregar un texto a los imputs antes de ser llenados por el usuario, aplica en inputs como el de texto

- Required
  - 
  es un atributo de funcionalidad, cuya función es hacer obligatorio rellenar el input para enviar el formulario

- Name
  -  
  funciona como un identificador, es util para funcionalidades que el desarrollador pueda ejecutar, relacionandolas con el nombre o "*name*"

- Otros atributos:
  - 
  - value
  - min
  - max



## CSS Básico

