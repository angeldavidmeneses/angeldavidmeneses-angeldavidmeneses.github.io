# angeldavidmeneses-angeldavidmeneses.github.io

Taller Introducción Aplicaciones Web
1.	¿Qué es HTML? 

HTML, que significa HyperText Markup Language (Lenguaje de Marcado de Hipertexto), es el lenguaje estándar utilizado para crear y diseñar páginas web. Su función principal es estructurar el contenido de la web mediante el uso de etiquetas (tags) que definen elementos como párrafos, encabezados, enlaces, imágenes, y otros tipos de contenido multimedia

¿cuál es su función en la web?

La función principal de HTML en la web es estructurar y organizar el contenido de las páginas web. utilizando etiquetas para definir elementos como párrafos, encabezados, listas, etc.
•	HTML organiza el contenido en una estructura lógica, utilizando etiquetas para definir elementos como párrafos, encabezados, listas, etc.
•	Permite la creación de hipervínculos que conectan diferentes páginas web, facilitando la navegación.
•	Facilita la inclusión de imágenes, videos y otros elementos multimedia en las páginas web.
•	Permite la creación de formularios interactivos para la recolección de datos del usuario.
•	Asegura que las páginas web se muestren correctamente en diferentes navegadores y dispositivos.


2. ¿Que es una etiqueta HTML y menciona las etiquetas más comunes? 

Las etiquetas HTML son los componentes básicos del lenguaje HTML. Se utilizan para definir y estructurar el contenido de una página web. Cada etiqueta está encerrada entre corchetes angulares (< >) y generalmente viene en pares: una etiqueta de apertura (<etiqueta>) y una etiqueta de cierre (</etiqueta>).

•	<html>: Define el inicio y el final de un documento HTML.
•	<head>: Contiene metadatos sobre el documento, como el título y enlaces a hojas de estilo.
•	<title>: Define el título de la página, que aparece en la pestaña del navegador.
•	<body>: Contiene el contenido principal de la página, como texto, imágenes y enlaces.
•	<h1> a <h6>: Etiquetas de encabezado, donde <h1> es el encabezado más importante y <h6> el menos importante.
•	<p>: Define un párrafo.
•	<a>: Define un enlace (hipervínculo).
•	<img>: Inserta una imagen.
•	<ul>: Define una lista no ordenada (con viñetas).
•	<ol>: Define una lista ordenada (numerada).
•	<li>: Define un elemento de lista.
•	<div>: Define una sección o división en el documento.
•	<span>: Define una sección en línea para aplicar estilos o scripts.
•	br>: Inserta un salto de línea.
•	form>: Define un formulario para la entrada de datos del usuario.
•	input>: Define un campo de entrada en un formulario.
•	button>: Define un botón interactivo

3. ¿Qué es un atributo de una etiqueta HTML y menciona los más comunes?

Un atributo en una etiqueta HTML proporciona información adicional sobre el elemento HTML. Los atributos se colocan dentro de la etiqueta de apertura y generalmente vienen en pares de nombre y valor, separados por un signo igual (=).

•	id: Asigna un identificador único a un elemento. Ejemplo: <div id="miDiv">.
•	class: Asigna una o más clases a un elemento, que pueden ser utilizadas para aplicar estilos CSS. Ejemplo: <p class="texto-grande">.
•	src: Especifica la URL de una imagen, archivo de video, o script. Ejemplo: <img src="imagen.jpg">.
•	href: Define la URL a la que apunta un enlace. Ejemplo: <a href="https://www.ejemplo.com">Enlace</a>.
•	alt: Proporciona un texto alternativo para una imagen, útil para accesibilidad. Ejemplo: <img src="imagen.jpg" alt="Descripción de la imagen">.
•	style: Aplica estilos CSS directamente al elemento. Ejemplo: <p style="color: red;">Texto en rojo</p>.
•	title: Proporciona información adicional que aparece como un tooltip cuando se pasa el cursor sobre el elemento. Ejemplo: <a href="#" title="Más información">Enlace</a>.
•	type: Especifica el tipo de entrada en un formulario. Ejemplo: <input type="text">.


4.	¿Qué es CSS y cómo se utiliza para el diseño web? 

CSS, que significa Cascading Style Sheets (Hojas de Estilo en Cascada), es un lenguaje utilizado para describir la presentación de un documento HTML. CSS controla cómo se muestran los elementos HTML en la pantalla, en papel o en otros medios.
 CSS permite aplicar estilos como colores, fuentes, tamaños de texto, márgenes, bordes y mucho más a los elementos HTML.
Facilita la creación de diseños complejos, como la disposición de elementos en columnas, filas, y la creación de diseños responsivos que se adaptan a diferentes tamaños de pantalla.
Mantiene el contenido HTML separado de la presentación visual, lo que hace que el código sea más limpio y fácil de mantener.
Permite definir estilos en un archivo CSS externo que puede ser reutilizado en múltiples páginas web, asegurando consistencia en el diseño.



5.	¿Que es una propiedad en CSS y menciona las propiedades más comunes?
Una propiedad en CSS es una característica específica que se puede aplicar a un elemento HTML para controlar su apariencia y estilo. Cada propiedad tiene un valor que define cómo se debe aplicar esa característica. Las propiedades se utilizan dentro de las reglas CSS para estilizar los elementos de una página web.

Propiedades más comunes en CSS
•	color: Define el color del texto.
p {
    color: blue;
}
•	background-color: Establece el color de fondo de un elemento.
div {
    background-color: yellow;
}

•	font-size: Define el tamaño de la fuente del texto.
h1 {
font-size: 24px;
}

•	margin: Establece el espacio exterior alrededor de un elemento.
.container {
    margin: 20px;
}

•	padding: Define el espacio interior dentro de un elemento.
.box {
    padding: 10px;
}

•	border: Establece el borde alrededor de un elemento.
img {
    border: 2px solid black;
}

•	width y height: Definen el ancho y la altura de un elemento.
.image {
    width: 100px;
    height: 100px;
}

•	text-align: Define la alineación del texto dentro de un elemento.
h2 {
    text-align: center;
}
•	display: Controla cómo se muestra un elemento en la página.
.hidden {
    display: none;
}


•	position: Define el método de posicionamiento de un elemento.
.fixed {
    position: fixed;
    top: 0;
    left: 0;
}


6.	¿Qué es un selector en CSS y cuales tipos existen? 

Un selector en CSS es una parte del código que se utiliza para seleccionar los elementos HTML a los que se aplicarán las reglas de estilo. Los selectores permiten aplicar estilos específicos a elementos específicos en una página web

Tipos de selectores en CSS
•	Selector de tipo: Selecciona todos los elementos de un tipo específico.
p {
color: blue;
}
•	Selector de clase: Selecciona elementos que tienen una clase específica. Se utiliza un punto (.) antes del nombre de la clase.

.miClase {
font-size: 20px;
}
•	Selector de ID: Selecciona un elemento con un ID específico. Se utiliza un símbolo de almohadilla (#) antes del nombre del ID.
#miID {
background-color: yellow;
}




•	Selector universal: Selecciona todos los elementos de la página.

{
margin: 0;
padding: 0;
}


•	Selector de atributo: Selecciona elementos que tienen un atributo específico.
input[type="text"] {
border: 1px solid black;
}

•	Selectores de descendiente: Selecciona elementos que son descendientes de un elemento específico.
div p {
color: green;
}

•	Selectores de hijo: Selecciona elementos que son hijos directos de un elemento específico.

ul > li {
list-style-type: none;
}

•	Selectores de hermano adyacente: Selecciona un elemento que es el siguiente hermano inmediato de un elemento específico.
h1 + p {
margin-top: 0;
}

•	Selectores de hermano general: Selecciona todos los elementos hermanos de un elemento específico.
h1 ~ p {
color: red;
}


7.	¿Qué es JavaScript y cómo añade la interactividad a las páginas web?

JavaScript es un lenguaje de programación que se utiliza para crear contenido dinámico e interactivo en las páginas web. A diferencia de HTML y CSS, que se encargan de la estructura y el diseño de una página, JavaScript permite añadir funcionalidades que responden a las acciones del usuario, haciendo que las páginas web sean más interactivas y atractivas.

Manipulación del DOM: JavaScript puede acceder y modificar el Document Object Model (DOM) de una página web, permitiendo cambiar el contenido y la estructura de la página en respuesta a las acciones del usuario.
JavaScript puede responder a eventos como clics, movimientos del ratón, teclas presionadas, etc; Permite crear animaciones y efectos visuales en la página; También puede enviar y recibir datos de un servidor sin necesidad de recargar la página, utilizando tecnologías como AJAX.


 
8.	¿Cuáles son los tipos de datos primitivos en Javascript? 

En JavaScript, los tipos de datos primitivos son los tipos de datos más básicos y fundamentales. Estos tipos de datos no son objetos y no tienen métodos

-number: Este tipo de dato incluye tanto números enteros como números de punto flotante (decimales). JavaScript no distingue entre estos dos tipos de números, todos se consideran del tipo number.

-string: Las cadenas de texto se utilizan para representar texto. Puedes definir una cadena utilizando comillas simples ('), comillas dobles ("), o comillas invertidas (`) para plantillas de cadena.

-boolean: Este tipo de dato solo tiene dos valores posibles: true o false. Se utiliza comúnmente en condiciones y bucles.

-undefined: Una variable que ha sido declarada pero no se le ha asignado un valor tiene el valor undefined. Esto indica que la variable existe pero aún no tiene un valor definido.

-null: Este valor representa la ausencia intencional de cualquier valor de objeto. Es diferente de undefined en el sentido de que null se asigna explícitamente a una variable para indicar que no tiene valor.

-symbol: Los símbolos son valores únicos y anónimos que se utilizan principalmente como identificadores únicos para las propiedades de los objetos. Cada símbolo es único, incluso si se crean con la misma descripción.

-bigint: Este tipo de dato se utiliza para representar números enteros de gran tamaño que no pueden ser representados con el tipo number. Se define agregando una n al final del número.


Características de los tipos de datos primitivos:
1)	Inmutabilidad: Los valores primitivos son inmutables, lo que significa que no pueden ser cambiados una vez creados. Por ejemplo, si cambias el valor de una cadena, en realidad estás creando una nueva cadena.
2)	Comparación por valor: Los valores primitivos se comparan por su valor. Dos valores primitivos son iguales si tienen el mismo valor.
3)	Almacenamiento en la pila: Los valores primitivos se almacenan en la pila de memoria, lo que permite un acceso rápido y eficiente


9.	¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en Javascript? 

Estructuras de Control Condicionales if y else

La estructura if se utiliza para ejecutar un bloque de código si una condición es verdadera. La estructura else se utiliza para ejecutar un bloque de código alternativo si la condición es falsa.

Ejemplo: 

let edad = 18;
if (edad >= 18) {
    console.log("Eres mayor de edad.");
} else {
    console.log("Eres menor de edad.");
}

else if
La estructura else if permite probar múltiples condiciones. Si la primera condición es falsa, se evalúa la siguiente condición, y así sucesivamente.

Ejemplo:

let nota = 85;
if (nota >= 90) {
    console.log("Excelente");
} else if (nota >= 75) {
    console.log("Bueno");
} else if (nota >= 50) {
    console.log("Aprobado");
} else {
    console.log("Reprobado");
}





switch
La estructura switch se utiliza para ejecutar uno de varios bloques de código en función del valor de una expresión. Es útil cuando se tienen muchas condiciones que dependen del mismo valor.

Ejemplo:
let dia = 3;
let nombreDia;

switch (dia) {
    case 1:
        nombreDia = "Lunes";
        break;
    case 2:
        nombreDia = "Martes";
        break;
    case 3:
        nombreDia = "Miércoles";
        break;
    case 4:
        nombreDia = "Jueves";
        break;
    case 5:
        nombreDia = "Viernes";
        break;
    case 6:
        nombreDia = "Sábado";
        break;
    case 7:
        nombreDia = "Domingo";
        break;
    default:
        nombreDia = "Día inválido";
}

console.log(nombreDia);





Bucles
for
El bucle for se utiliza para ejecutar un bloque de código un número específico de veces. Se compone de tres partes: inicialización, condición y actualización.
Ejemplo:

for (let i = 0; i < 5; i++) {
    console.log("Iteración número " + i);
}

while
El bucle while ejecuta un bloque de código mientras una condición sea verdadera. La condición se evalúa antes de cada iteración.

let contador = 0;

while (contador < 5) {
    console.log("Contador: " + contador);
    contador++;
}

do...while
El bucle do...while es similar al while, pero la condición se evalúa después de cada iteración, lo que garantiza que el bloque de código se ejecute al menos una vez.

let numero = 0;

do {
    console.log("Número: " + numero);
    numero++;
} while (numero < 5);


10.	¿Por qué es importante usar nombres significativos para variables y métodos? 

Facilita la comprensión. Nombres descriptivos ayudan a otros desarrolladores (y a uno mismo en el futuro) a entender rápidamente qué hace una variable o método sin necesidad de leer todo el código, Un código con nombres claros es más fácil de mantener y actualizar. Los desarrolladores pueden identificar rápidamente qué partes del código necesitan cambios En proyectos de equipo, nombres significativos permiten que todos los miembros del equipo entiendan el código sin necesidad de explicaciones adicionales.

11.	¿Qué es una variable de entorno y por qué son importantes para Javascript o la programación en general? 

Una variable de entorno es una variable dinámica que puede afectar el comportamiento de los procesos en un sistema operativo. Estas variables se utilizan para almacenar información que puede ser utilizada por aplicaciones y scripts durante su ejecución. En el contexto de la programación, incluidas aplicaciones JavaScript, las variables de entorno son esenciales por varias razones:

Funciones de las Variables de Entorno

-Configuración del Entorno: Permiten configurar el entorno de ejecución de una aplicación sin necesidad de modificar el código fuente. Esto es útil para cambiar configuraciones entre diferentes entornos (desarrollo, pruebas, producción).

-Seguridad: Ayudan a mantener información sensible, como claves API, contraseñas y otros secretos, fuera del código fuente. Esto reduce el riesgo de exposición accidental de datos sensibles.

-Portabilidad: Facilitan la portabilidad de aplicaciones entre diferentes sistemas y entornos, ya que las configuraciones específicas del entorno se pueden ajustar sin cambiar el código.



12.	¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas? 

Las herramientas de desarrollo de Chrome, conocidas como Chrome DevTools, son un conjunto de herramientas integradas directamente en el navegador Google Chrome. Estas herramientas están diseñadas para ayudar a los desarrolladores web a editar páginas sobre la marcha, diagnosticar problemas rápidamente y optimizar el rendimiento de sus sitios web.

Funciones de Chrome DevTools

1)	Inspección y edición del DOM: Permite ver y modificar la estructura del documento HTML y los estilos CSS en tiempo real.
2)	Consola: Proporciona un entorno para ejecutar comandos JavaScript y ver mensajes de registro.
3)	Depuración: Facilita la depuración de código JavaScript, permitiendo establecer puntos de interrupción y seguir la ejecución del código paso a paso.
4)	Red: Muestra todas las solicitudes de red realizadas por la página, incluyendo tiempos de carga y detalles de cada solicitud.
5)	Rendimiento: Permite analizar y optimizar el rendimiento de la página, identificando cuellos de botella y problemas de rendimiento.
6)	Memoria: Ayuda a detectar y solucionar problemas de memoria, como fugas de memoria.
7)	Aplicación: Inspecciona y depura aplicaciones web, incluyendo almacenamiento local, cookies y caché.
8)	Seguridad: Verifica que la página esté completamente protegida por HTTPS y detecta problemas de seguridad.


Cómo acceder a las herramientas de desarrollo de Chrome

Existen varias formas de abrir Chrome DevTools:

1)	Menú de Chrome:
Haz clic en los tres puntos verticales en la esquina superior derecha del navegador.
Selecciona “Más herramientas” y luego “Herramientas para desarrolladores”.

2)	Atajos de teclado:
Windows/Linux: Ctrl + Shift + I o F12
Mac: Cmd + Option + I

3)	Clic derecho:
Haz clic derecho en cualquier parte de la página web y selecciona “Inspeccionar”.

13.	 ¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo? 

El panel “Elements” de las herramientas de desarrollo de Chrome (Chrome DevTools) es una herramienta poderosa que permite inspeccionar y editar el Document Object Model (DOM) y los estilos CSS de una página web en tiempo real.

Inspección del DOM: Puedes ver la estructura del DOM de la página, que se asemeja a un documento HTML. Esto te permite seleccionar y examinar cualquier nodo del DOM.
-Editar HTML: Puedes hacer doble clic en cualquier elemento del DOM para editar su HTML directamente.
-Agregar o eliminar elementos: Puedes agregar nuevos elementos HTML o eliminar los existentes.
-Estilos CSS: En la pestaña “Styles”, puedes ver y editar las reglas de CSS aplicadas al elemento seleccionado.
-Modificar estilos: Puedes cambiar los valores de las propiedades CSS y ver los cambios en tiempo real.
-Agregar nuevas reglas: Puedes agregar nuevas reglas CSS para el elemento seleccionado.
-Ver estilos calculados: En la pestaña “Computed”, puedes ver las propiedades CSS calculadas que se aplican al elemento.
-Visualiza el modelo de caja de CSS, que muestra el margen, borde, padding y tamaño del contenido del elemento seleccionado.
-Ajustar dimensiones: Puedes ajustar visualmente las dimensiones del margen, borde y padding.
-Depurar eventos: Puedes ver y depurar los controladores de eventos.
Accesibilidad: Inspecciona las propiedades de accesibilidad de los elementos, como las etiquetas ARIA.
- Puedes establecer puntos de interrupción en el DOM para depurar cambios específicos en la estructura del documento.
-Monitorear cambios: Puedes monitorear y depurar cambios en el DOM en tiempo real.


14.	 ¿Cómo se utiliza el panel "Console" de las herramientas de desarrollo y para qué es útil? 
El panel “Console” de las herramientas de desarrollo de Chrome (Chrome DevTools) es una herramienta esencial para los desarrolladores web. Permite interactuar con la página web mediante comandos JavaScript, ver mensajes de registro y depurar errores.

Funcionalidades del Panel “Console”

1). Ver mensajes de registro: Puedes usar console.log() para registrar mensajes en la consola. Esto es útil para depurar y verificar que tu código se está ejecutando correctamente. 
console.log('Hola, Console!');

2). Ejecutar comandos JavaScript: La consola actúa como un entorno REPL (Read-Eval-Print Loop), lo que significa que puedes escribir y ejecutar comandos JavaScript directamente.

3). Depuración de errores: La consola muestra errores y advertencias en tu código, lo que te ayuda a identificar y solucionar problemas rápidamente.

4). Inspección de elementos: Puedes seleccionar elementos del DOM y manipularlos directamente desde la consola.

5). Uso de métodos avanzados: La consola ofrece varios métodos útiles para depuración avanzada, como console.table() para mostrar datos en formato de tabla y console.assert() para realizar afirmaciones condicionales.




15.	¿Qué información se puede obtener del panel "Network" y por qué es importante?

El panel “Network” de las herramientas de desarrollo de Chrome (Chrome DevTools) es una herramienta esencial para analizar y depurar la actividad de red de una página web. 
Del panel “Network” se puede obtener:
Solicitudes de red: Muestra todas las solicitudes de red realizadas por la página, incluyendo archivos HTML, CSS, JavaScript, imágenes, y otros recursos.
Método HTTP: El método utilizado para la solicitud (GET, POST, etc.).
Estado: El código de estado HTTP de la respuesta (200, 404, 500, etc.).
Tipo: El tipo de recurso solicitado (documento, script, imagen, etc.).
Iniciador: La causa de la solicitud, como el archivo o script que la inició.
Tamaño: La cantidad de datos transferidos.
Tiempo: El tiempo que tardó en completarse la solicitud.
Encabezados HTTP: Detalles de los encabezados de solicitud y respuesta, que incluyen información como el tipo de contenido, cookies, y más.
Encabezados de solicitud: Información enviada al servidor, como User-Agent, Accept, etc.
Encabezados de respuesta: Información devuelta por el servidor, como Content-Type, Set-Cookie, etc.
Carga útil: Los datos enviados en el cuerpo de la solicitud, como los datos de formularios en solicitudes POST.
Parámetros de consulta: Datos enviados en la URL de la solicitud.
Datos del formulario: Información enviada en el cuerpo de la solicitud.
Tiempo de carga: Un desglose detallado del tiempo que tomó cada fase de la solicitud, incluyendo el tiempo de conexión, el tiempo de espera del servidor, y el tiempo de descarga.
DNS Lookup: Tiempo para resolver el nombre de dominio.
Conexión: Tiempo para establecer la conexión TCP.
TLS: Tiempo para establecer la conexión segura (si aplica).
Waiting (TTFB): Tiempo de espera hasta el primer byte de respuesta.
Content Download: Tiempo para descargar el contenido.
Cookies: Información sobre las cookies enviadas y recibidas en la solicitud.
Nombre y valor: Nombre y valor de cada cookie.
Dominio y ruta: Dominio y ruta para los que la cookie es válida.
Fecha de expiración: Fecha en la que la cookie expira.
Vista previa y respuesta: Permite ver una vista previa del contenido de la respuesta y el código fuente del recurso.
Vista previa: Renderización básica del HTML o JSON.
Respuesta: Código fuente del recurso devuelto.

Importancia del panel “Network”

1)	Diagnóstico de problemas de carga: Ayuda a identificar y solucionar problemas relacionados con la carga de recursos, como archivos que no se cargan, tiempos de carga lentos, y errores de red
2)	Optimización del rendimiento: Permite analizar el rendimiento de la red y optimizar la carga de recursos para mejorar la velocidad de la página
3)	Depuración de solicitudes AJAX: Facilita la depuración de solicitudes asíncronas (AJAX) y la verificación de datos enviados y recibidos
4)	Seguridad: Ayuda a verificar que las solicitudes se realicen de manera segura, revisando encabezados de seguridad y cookies
5)	Análisis de tráfico: Permite analizar el tráfico de red para entender mejor cómo se comunican los diferentes componentes de la aplicación
