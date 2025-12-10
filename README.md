# PORTAFOLIO-MOD-4-AGENDA


Evaluación de portafolio
Contexto del Proyecto:
Eres parte del equipo de desarrollo de una pequeña empresa que administra una agenda digital para empleados. Esta herramienta permite registrar citas importantes, tareas pendientes y reuniones. Como parte del equipo, tu responsabilidad es desarrollar una aplicación de consola en Java que permita gestionar dicha agenda.

El sistema debe permitir a los usuarios agregar tareas con una fecha, descripción y estado (pendiente/completada), mostrar todas las tareas, filtrar por estado, y marcar tareas como completadas. Además, deberás aplicar conceptos de Programación Orientada a Objetos (POO) para modelar el sistema y escribir pruebas unitarias con JUnit para asegurar que las clases principales funcionan correctamente.

Instrucciones:
Análisis del lenguaje Java y sintaxis básica

Realiza una breve investigación (puede ser en equipo) sobre las principales características del lenguaje Java para el desarrollo de aplicaciones empresariales.

Menciona por escrito:

¿Qué lo hace adecuado para este tipo de aplicaciones?

¿Qué ventajas ofrece respecto a otros lenguajes?

Comenta en clase tus conclusiones (puede ser parte del entregable también).

Estructura del algoritmo lógico (control y expresiones):

Define en pseudocódigo o diagrama de flujo un algoritmo simple que:

Agregue una tarea si el usuario la solicita.

Muestre un menú interactivo con opciones como “Agregar”, “Listar”, “Filtrar”, “Marcar completada”, “Salir”.

Asegúrate de usar estructuras de control (if, switch, while, etc.) para controlar el flujo.

Después, implementa esa lógica usando la sintaxis de Java.

Desarrollo de la aplicación de consola en Java:

La aplicación debe ejecutarse en consola.

Debe permitir:

Agregar una nueva tarea (descripción, fecha, estado)

Listar todas las tareas

Filtrar tareas por estado

Marcar una tarea como completada

Utiliza Scanner para entrada de datos y buenas prácticas de codificación (nombres de clases, indentación, comentarios claros).

Uso de Programación Orientada a Objetos:

Crea al menos las siguientes clases:

Tarea: con atributos como descripción, fecha, estado, e identificador único.

Agenda: con métodos para agregar, listar, filtrar, y actualizar tareas.

Main: donde se ejecuta la aplicación principal.

Aplica principios de diseño como encapsulamiento, separación de responsabilidades, y reutilización de código.

Principios básicos de diseño orientado a objetos:

Asegúrate de usar:

Encapsulamiento (private, getters/setters).

Composición (la Agenda contiene varias Tarea).

Métodos que sigan la convención de una sola responsabilidad.

Comenta el código para explicar cómo aplicaste esos principios.

Pruebas unitarias con JUnit:

Instala JUnit en tu entorno de desarrollo (puede ser con Maven o manual).

Crea pruebas para:

Verificar que se agrega correctamente una tarea.

Verificar que se puede filtrar correctamente por estado.

Verificar que una tarea puede cambiar su estado a completada.

Asegúrate de correr todas las pruebas y documentar los resultados.
