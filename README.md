![Inove banner](/inove.jpg)
Inove Escuela de Código\
info@inove.com.ar\
Web: [Inove](http://inove.com.ar)

# Trivia [Python_2]
Juego en donde el programa hace preguntas a jugadores, los cuales deberán elegir por multiple choice (4 posibles respuestas por pregunta). Al finalizar gana el jugador con más respuesta acertadas.\
Mínimo el programa debe soportar 2 jugadores.

Este proyecto está basado en el proyecto de Python Inicial:\
[https://github.com/InoveAlumnos/trivia_python_1](https://github.com/InoveAlumnos/trivia_python_1)

La diferencia radica en que ahora no se utilizará un CSV de entrada o de salida sinó que se solicitará transformar el CSV en una base de datos.

# Entrada del sistema
El programa recibe un archivo “csv” en donde se colocará las preguntas que del juego, las 4 posibles respuestas y la en cada caso cuál es la respuesta correcta (número del 1 al 4). Este archivo el alumno lo transformar en una base de datos.\
El archivo consta de una fila por pregunta, 6 columnas por fila (pregunta, 4 respuestas, respuesta correcta).\
Puede agregarse si se desea más detalles como categorías o cualquier cosa que el alumno crea que puede sumar al programa.\

__Archivo CSV de ejemplo para usar como referencia__\
preguntas.csv

# Salida del sistema
Al finalizar el programa se deberá presentar los resultados de cuántas preguntas correctas realizó cada jugador y el ganador del juego, dando un puntaje final a cada uno.\
El juego se realizo todo por API y HTTP, cada jugar al entrar al juego recibe una pregunta la contestarla. Después de contestar esa pregunta el juego deberá mostrarle la siguiente.\
La respuesta de cada pregunta debe venir acompañada con el nombre del jugador que la responde, así en una base de datos se anota el puntaje de cada jugar y cuantas preguntas ya respondió.\
Al final del juego el sistema deberá retorar a ese jugar su puntaje total para que compare contra los otros jugadores.

# Notas
Este proyecto puede utilizarse como base o referencia para hacer uno parecido o distinto del mismo tema. Se solicita que el contenído mínimo del proyecto alcance los especificado en las "entradas y salida del sistema" pudiendo el alumno modificar o agregar requerimientos. El objetivo en este proyecto es que construyan una base de datos y manipulen al menos dos jugadores y sus respuestas por HTTP.\
En cada caso puntual se discutirá con el alumno como puede ser modificado el proyecto según sus deseos o necesidades.

Estos temas se discuten en el campus del curso en el foro correspondiente al proyecto. Cada alumno deberá iniciar un tema de discucisión sobre el proyecto que desea realizar y como este lo desea implementar.

# Consultas
alumnos@inove.com.ar

