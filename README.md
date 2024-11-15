Descripción del Proyecto
Esta es una calculadora interactiva desarrollada en JavaScript que permite realizar operaciones
matemáticas básicas, manejando errores y mostrando un historial de operaciones. El proyecto
está diseñado para ser ejecutado en la consola del navegador, utilizando una interfaz textual
sencilla a través de prompt.

Funcionalidades
La calculadora ofrece las siguientes características:
Operaciones Matemáticas Básicas:
Suma
Resta
Multiplicación
División
Raíz Cuadrada
Manejo de Errores:
Validación de inputs para asegurarse de que los datos ingresados son numéricos.
Manejo de errores como la división por cero.
Historial de Operaciones:
Guarda un registro de todas las operaciones realizadas durante la sesión.
Permite al usuario consultar el historial de operaciones.
Repetición de Operaciones:
La calculadora se mantiene activa hasta que el usuario decida salir, permitiendo realizar
múltiples operaciones en una sola sesión.

Requisitos del Sistema
Navegador moderno: Google Chrome, Mozilla Firefox, Microsoft Edge, o Safari.
No se necesita conexión a Internet, ya que el proyecto es independiente de servidor.

Cómo Ejecutar el Proyecto
Descarga y descomprime el archivo .zip del proyecto.
Abre el archivo index.html en tu navegador.
Abre la consola del navegador (clic derecho > Inspeccionar > Consola).
Sigue las instrucciones que aparecen en la consola para realizar operaciones

Instrucciones de Uso
Al iniciar, se mostrará un menú interactivo en la consola con las opciones disponibles.
Elige una operación ingresando el número correspondiente:
1: Suma
2: Resta
3: Multiplicación
4: División
5: Raíz Cuadrada
6: Ver Historial de Operaciones
0: Salir de la calculadora
Sigue las instrucciones para ingresar los números.
El resultado se mostrará en la consola y se guardará en el historial.
Puedes ver el historial seleccionando la opción 6.

Manejo de Errores
Entrada no numérica: Si el usuario ingresa un valor que no es un número, se mostrará un
mensaje de error y la operación no se realizará.
División por cero: Si se intenta dividir por cero, se mostrará un mensaje de error y el resultado
no se guardará en el historial.
Número negativo para raíz cuadrada: Si se ingresa un número negativo para calcular la raíz
cuadrada, se mostrará un mensaje de error.

Historial de Operaciones
El historial se guarda en un array y se puede visualizar en cualquier momento durante la sesión.
Al cerrar la página o recargarla, el historial se perderá, ya que no se guarda de manera
persistente.

Decisiones de Diseño
Interacción con el usuario: Se utiliza prompt y la consola del navegador para mantener la
simplicidad del proyecto.
Validación de datos: Se implementan funciones para validar que los inputs sean numéricos y
para manejar errores comunes como la división por cero.
Diseño modular: El código se divide en funciones específicas para cada operación, siguiendo
las buenas prácticas de programación.

Recursos y Herramientas
Editor de código recomendado: Visual Studio Code
Diagrama de Casos de Uso: Creado con draw.io
Navegadores compatibles: Chrome, Firefox, Edge, Safari

Desafíos Encontrados
Validación de inputs: Implementar un sistema robusto de validación para manejar inputs no
numéricos y errores comunes.
Manejo del historial: Crear una estructura eficiente para almacenar y mostrar el historial de
operaciones.
Modularidad del código: Asegurar que cada función tenga una sola responsabilidad, facilitando
el mantenimiento y la legibilidad del código.
