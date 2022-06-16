# Arquitectura de Sistemas
Obligatorio de arquitectura de sistemas 2022.

## Autores
Federico Gutiérrez (262684)

Santiago González (238993)


## Instrucciones de uso
Primero se debe descargar el programa [Logisim](http://www.cburch.com/logisim/download.html) para poder abrir los archivos `.circ`

Una vez instalado, se abre el cicuito que se desee (tanto el Semáforo como la Máquina) 

## Semáforo
Para comenzar a utilizarlo basta con activar el reloj  ( `Ctrl + k` o en el menú "Simular" -> Activar reloj). 

## Máquina 
La máquina es capaz dew realizar las siguientes operaciones, dependiendo de la entrada ingresada en ABC. Estas operaciones son:
1)	ABC = 000: Guardar la palabra GHI en la dirección DEF.
2)	ABC = 001: Muestra en la salida la palabra almacenada en la dirección DEF.
3)	ABC = 010: Muestra en la salida el resultado de la suma binaria de 3 bits de GHI + DEF.
4)	ABC = 011: Resolver la función DEF/G+ DEFG+ /DEF/G + D/E/FG +/D/E/F/G.
5)	ABC = 100: Se borra cada palabra de la memoria interna.
6)	ABC = 101: Muestra 1 en caso de que la palabra DEFGHI contenga una cantidad impar de dígitos 1.
7)	ABC = 110: Invierte DEF y le suma 1 (procedimiento equivalente a buscar el complemento), muestra el resultado en la salida de 3 bits.
8)	ABC = 111: Resta DE - FG. Para el caso de que el valor sea negativo, se prende la bandera de overflow y se descarta el resultado.

### Pasos para un uso correcto
1) Verificar que "botón" etiquedato **ENV** se encuentre apagado
2) Ingresar la operación deseada en ABC
3) Cargar los datos deseados en DEF GHI
4) Activar el "botón" **ENV** para ver los resultados de la operación indicada. 
5) Para continuar realizando operaciones, reiterar desde el paso 1

