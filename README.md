# Programa Capaz de Restaurar Estado de Ejecucion
Materia: Computación Tolerante a Fallas<br>
Maestro: MICHEL EMANUEL LOPEZ FRANCO<br>
Nombre: Diego Alonso Mercado Brizuela<br>
Carrera: Ingeniería en Computación<br>
Código: 215425636<br>
Fecha: 2/09/2023<br>
Sección: D06<br>

## Introducción
Restaurar el programa puede ayudar a prevenir que si ocurre un error, la información no se pierda y el usuario no se sienta frustrado de ninguna manera, esto haciendo un respaldo en el dispositivo del usuario o en la computadora.
## Pruebas en Android Studio
Si se tienen pocos datos por guardar, como un formulario en donde se guardan los campos que el usuario llenó. En Android Studio existe una API llamada SharedPreferences que permite guardar estos datos como una colección y lo guarda en el dispositivo como si fuese caché.
Este es el formulario que llenerá el usuario
<br>
<img
src="https://github.com/Diego3207/Programa-Capaz-de-Restaurar-Estado-de-Ejecucion/blob/main/Formulario.png">
<br>
La idea es que cada 10 segundos que el usuario pase en la aplicación, se guardará en el dispositivo los campos con información. Si el usuario no ha llenado nada, se conserva así, pero si llena por ejemplo el campo "Animal", al pasar el tiempo se guardará, y si cerramos la aplicación se abrirá en el estado en el que lo dejó el usuario.
## Ejemplo 1
El campo fué llenado con Araña
<br>
<img
src="https://github.com/Diego3207/Programa-Capaz-de-Restaurar-Estado-de-Ejecucion/blob/main/Ara%C3%B1aGuardar.jpg" height="20%">
<br>
En este campo se ve que se guardó la información si se cerró el programa
<br>
<img
src="https://github.com/Diego3207/Programa-Capaz-de-Restaurar-Estado-de-Ejecucion/blob/main/ara%C3%B1aGuardada.jpg">
## Ejemplo 2
En este caso el campo que se llenó es el de alimentación
<br>
<img
src="https://github.com/Diego3207/Programa-Capaz-de-Restaurar-Estado-de-Ejecucion/blob/main/AlimentacionGuardar.jpg">
<br>
<img
src="https://github.com/Diego3207/Programa-Capaz-de-Restaurar-Estado-de-Ejecucion/blob/main/AlimentacionGuardada.jpg">
# Conclusiones
Si lo pensamos hay muchas maneras de guardar el estado de un programa, dependiendo de con qué lenguaje estemos trabajando, ya sea con archivos .txt o con diccionarios .json para guardar la información y que el usuario no se sienta frustrado o el proceso sea tedioso en cuestión de funcionamiento.
