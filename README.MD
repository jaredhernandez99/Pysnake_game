# Bienvenidos a  PySnake Game

Hola, estoy muy emocionado de subir mi primer juego:  **PySnake Game**. A github, se que es algo sencillo, pero es un juego que me emociona bastante compartir con ustedes. Les cuento un poco de como jugar, aunque solo se requiere de sentido común.

## Como Jugar

PySnake Game, es un juego que se puede jugar de dos maneras, la que nos acostumbramos mas actualmente que es con las teclas de **w,a,s,d** o las flechas del teclado **←, →, ↓, ↑**. Se puede jugar de ambos modos, personalmente se me hace más comodo con las letras, cuestión de gustos.

## Como ejecutar el juego

Se debe tener instalado Python ^3.x.  

*Se puede jugar unicamente corriendo el archivo main.py*


## Empaquetar el juego

Primeramente se debe de tener instalado una libreria de Python, que se llama PyInstaller, se instala de la siguiente manera: 
```
pip install pyinstaller
```
 Se recomienda instalar de manera global.
Una ves instalado, ejecutamos el siguiente codigo:
```
pyinstaller -i xxx.ico -F xxx.py
``` 
- -i es el icono que le queramos dar a nuestro ejecutable.
- -F es nuestro archivo, en este caso, todo recae sobre el main.py, este es al archivo al cual harán referencia.

Listo, a disfrutar. 
