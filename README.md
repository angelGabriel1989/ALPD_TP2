# ALPD_TP2


Enunciado
Para este trabajo se mantendrán el formato de ambos archivos y la forma de calcular los
puntos. Sin embargo, los equipos ya no se guardarán en un vector sino en una lista dinámica que
deberá ser creada por completo por ustedes y deberá mantener el orden alfabético.
Modificaciones
Como se detectaron errores en los partidos se pide incorporar 3 nuevas opciones en el menú:
agregar, eliminar y modificar partido.
Además, se deberá guardar la información de cada partido de cada fase para poder modificarlos.
Para esto se podrán tomar uno de dos caminos:
• Cada equipo tendrá un vector/lista con las fases en las que participó y por cada fase un
vector/lista con los partidos que jugó en la misma (se permitirá el uso de la biblioteca vector
si se implementa con vectores)
• Cada fase tendrá los partidos que se jugo en la misma y cada partido tendrá una referencia
al equipo que participo en él.
NOTA: Fase y/o Equipo deberán ser un objeto y se deberá utilizar herencia y polimorfismo para que
cada fase/equipo tenga su comportamiento, por ejemplo, saber calcular su puntaje y no guardar
parámetros innecesarios como serían los penales en fase de grupos.
Menú
Una vez leídos ambos archivos se deberá armar un programa que cuente con el siguiente menú:
1. Listar equipos.
2. Mostrar los equipos en primer segundo y tercer lugar.
3. Buscar equipo por nombre.
4. Mostrar por fase los países ordenados por puntaje.
5. Actualizar partidos
6. Salir y guardar.
Listar equipos
Se deberán listar todos los equipos en el orden en el cual estén guardados con su nombre y
grupo al que pertenecieron.
Mostrar los equipos en primer segundo y tercer lugar
Se deberá mostrar el nombre del equipo ganador, el segundo puesto y el tercer puesto del
mundial con los puntos totales que obtuvo cada uno en el torneo.
NOTA: la victoria no es necesariamente de aquel con más puntos sino de aquel que gano la fase
“final”, el tercer puesto es de aquel que gano la fase “tercer puesto”
Buscar equipo por nombre
Se le deberá pedir al usuario que ingrese el nombre de un equipo, si el mismo no se
encuentra entre los equipos participantes se le avisara que no hubo coincidencias.
2
Si hay una coincidencia se le mostrará el nombre, grupo al que perteneció, fase hasta la que
llegó y titulo obtenido en caso de obtener alguno (campeón, subcampeón, tercer puesto o cuarto
puesto).
Mostrar por fase los países ordenados por puntaje
Se deberá mostrar para la fase de grupos por cada grupo el nombre de cada selección
ordenadas por el puntaje obtenido. En el resto de las fases no se diferenciará a que grupo
perteneció cada selección, se mostraran todas juntas ordenadas por el puntaje obtenido en dicha
fase.
Actualizar partidos
En caso de seleccionar esta opción se mostrará un nuevo menú con tres opciones:
1. Agregar partido
2. Modificar partido
3. Eliminar partido
Agregar partido
Se le debe pedir al usuario la fase, el país de cada equipo, los goles y si hubo penales pedir el
puntaje. Si indica que no hubo penales se pone -1.
Se debe analizar los posibles errores y tomar decisiones que sean amigables con el usuario,
por ejemplo, si pone un número negativo de goles o más de 20 pedir que reingrese los valores.
Modificar partido
Se le debe preguntar la fase (grupos, octavos, cuartos, semifinal, final o tercer puesto) y los
equipos. Si se encuentra el partido se le debe pedir que indique si desea modificar los goles o los
equipos.
Si modifica equipos se le dejará seleccionar que equipo cambiar y se le pedirá el nombre del
equipo correcto. En caso de que seleccione goles se le pedirá la cantidad de cada equipo y los
penales si fueran necesarios.
Eliminar partido
Se le debe preguntar la fase (grupos, octavos, cuartos, semifinal, final o tercer puesto) y los
equipos. Si se encuentra el partido se deberá eliminar el mismo o mostrar error en caso contrario.
Salir
Despedirse del usuario y finalizar el programa liberando cualquier memoria que se haya
pedido y modificando los archivos en caso de ser necesario.
UML
Se deberá entregar como mínimo DOS UMLs, uno esquelético de toda la aplicación y otro
que muestre la herencia entre las fases. Se pueden agregar más de considerarlo necesario.
Aclaraciones importantes
• NO se puede usar una biblioteca para listas.
• Se deberá desarrollar utilizando POO (programación orientada a objetos).
• Los vectores deben crearse utilizando memoria dinámica. La misma se debe liberar al final
del programa.
• El trabajo es de carácter individual.
3
• Se valorará, entre otras cosas, la eficiencia del algoritmo.
• No se deben subir archivos de configuración de los IDEs (solo subir .cpp y .h).
• El trabajo debe compilar con los flags -Wall -Werror -Wconversion.
¿Qué se evaluará?
• Compilación: sin warnings ni errores.
• Funcionalidad.
• Eficiencia espacial.
• Eficiencia temporal.
• Buenas prácticas de programación (nombres descriptivos, indentación, etc.).
• Separación de operadores.
• Modularización.
• Precondiciones y postcondiciones.
• Uso de memoria dinámica
• Manejo de listas
• POO
Normas de entrega
Se deberá subir al campus un único archivo comprimido (.zip) en la sección TPs.
Este archivo deberá tener un nombre formado de la siguiente manera:
Padron_Apellido_TP2
Por ejemplo:
110204_Perez_TP2.zip
El archivo deberá contener solo los archivos fuente. Es decir, solo .cpp y .h. NO subir los archivos de
configuración de sus IDEs. (por ejemplo: CMakeList y cmake-build para Clion, .vscode para
VisualStudioCode).
La fecha de entrega vence el miércoles 10 de mayo a las 23.55hs.
Puntaje: 60 Puntos.
