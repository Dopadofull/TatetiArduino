# tatetiArduino

## Definiciones de Leds RGB

```
#define B11 41
#define G11 39
#define R11 37
```
```#define B11 41``` esta definiendo el led Blue(Azul) de la primera fila de la primera columna, con el pin 41

```#define G11 39``` esta definiendo el led Green(Verde) de la primera fila de la primera columna, con el pin 39

```#define R11 37``` esta definiendo el led Red(Rojo) de la primera fila de la primera columna, con el pin 37

```
#define B12 49
#define G12 51
#define R12 53
```

```#define B12 49``` esta definiendo el led Blue(Azul) de la primera fila de la segunda columna, con el pin 49

```#define G12 51``` esta definiendo el led Green(Verde) de la primera fila de la segunda columna, con el pin 51

```#define R12 53``` esta definiendo el led Red(Rojo) de la primera fila de la segunda columna, con el pin 53

```
#define B13 A7
#define G13 A8
#define R13 A9
```
```#define B13 A7``` esta definiendo el led Blue(Azul) de la primera fila de la tercera columna, con el pin analogico A7

```#define G13 A8``` esta definiendo el led Green(Verde) de la primera fila de la tercera columna, con el pin analogoco A8

```#define R13 A9``` esta definiendo el led Red(Rojo) de la primera fila de la tercera columna, con el pin analagico A9

```
#define B21 35
#define G21 33
#define R21 31
```
```#define B21 35``` esta definiendo el led Blue(Azul) de la segunda fila de la primera tecla columna, con el pin 35

```#define G21 33``` esta definiendo el led Green(Verde) de la segunda fila de la primera columna, con el pin 33

```#define R21 31``` esta definiendo el led Red(Rojo) de la segunda fila de la primera columna, con el pin 31

```
#define B22 47
#define G22 45
#define R22 43
```
```#define B22 47``` esta definiendo el led Blue(Azul) de la segunda fila de la segunda columna, con el pin 47

```#define G22 45``` esta definiendo el led Green(Verde) de la segunda fila de la segunda columna, con el pin 45

```#define R22 43``` esta definiendo el led Red(Rojo) de la segunda fila de la segunda columna, con el pin 43

```

#define B23 A10
#define G23 A11
#define R23 A12
```
```#define B23 A10``` esta definiendo el led Blue(Azul) de la segunda fila de la tercera columna, con el pin analogico A10

```#define G23 A11``` esta definiendo el led Green(Verde) de la segunda fila de la tercera columna, con el pin analogico A11

```#define R23 A12``` esta definiendo el led Red(Rojo) de la segunda fila de la tercera columna, con el pin analogico A12

```
#define B31 29
#define G31 27
#define R31 25
```
```#define B31 29``` esta definiendo el led Blue(Azul) de la tercera fila de la primera columna, con el pin 29

```#define G31 27``` esta definiendo el led Green(Verde) de la tercera fila de la primera columna, con el pin 27

```#define R31 25``` esta definiendo el led Red(Rojo) de la tercera fila de la primera columna, con el pin 25

```
#define B32 22
#define G32 24
#define R32 23
```
```#define B32 22``` esta definiendo el led Blue(Azul) de la tercera fila de la segunda columna, con el pin 22

```#define G32 24``` esta definiendo el led Green(Verde) de la tercera fila de la segunda columna, con el pin 24

```#define R32 23``` esta definiendo el led Red(Rojo) de la tercera fila de la segunda columna, con el pin 23

```
#define B33 A6
#define G33 A5
#define R33 A4
```
```#define B33 A6``` esta definiendo el led Blue(Azul) de la tercera fila de la tercera columna, con el pin analogico A6

```#define G33 A5``` esta definiendo el led Green(Verde) de la tercera fila de la tercera columna, con el pin analogico A5

```#define R33 A4``` esta definiendo el led Red(Rojo) de la tercera fila de la tercera columna, con el pin analogico A4

```
#define BLT A13
#define GLT A14
#define RLT A15
```
```#define BLT A13``` esta definiendo el led Blue(Azul) el primer led que se ve en el TatetiArduino indica el turno del jugador BLT(led blue turno), en el pin analogico A13

```#define G33 A5``` esta definiendo el led Blue(Azul) el primer led que se ve en el TatetiArduino indica el turno del jugador BLT(led blue turno), en el pin analogico A14

```#define R33 A4``` esta definiendo el led Blue(Azul) el primer led que se ve en el TatetiArduino indica el turno del jugador BLT(led blue turno), en el pin analogico A15

## Definicion Buzzer

```
#define BUZ 38
```
```#define BUZ 38``` esta definiendo el buzzer que emite el sonido, con el pin 38

## Pines Teclado Matricial

```
#define C1 2
#define C2 18
#define C3 19
#define F1 14
#define F2 15
#define F3 16
#define F4 17
```

```#define C1 2``` este define la columna 1 (C1) del teclado matricial, con el pin 2

```#define C2 18``` este define la columna 2 (C2) del teclado matricial, con el pin 18

```#define C3 19``` este define la columna 3 (C3) del teclado matricial, con el pin 19

```#define F1 14``` este define la fila 1 (F14) del teclado matricial, con el pin 14

```#define F2 15``` este define la fila 2 (F15) del teclado matricial, con el pin 15

```#define F3 16``` este define la fila 3 (F16) del teclado matricial, con el pin 16

```#define F4 17``` este define la fila 4 (F17) del teclado matricial, con el pin 17

```
#include <Keypad.h>
```
```#include <Keypad.h>``` incluye la biblioteca "keypad.h" 

```
const byte FILASLEDS = 3;
const byte COLUMNASLEDS = 3;
```
```#const byte FILASLEDS = 3;``` Aqui esta mostrando la cantidad de filas que hay en total en los leds, en este caso tenemos 3 filas de leds 

```#const byte COLUMNASLEDS = 3;``` Aqui esta mostrando la cantidad de columnas que hay en total en los leds, en este caso tenemos 3 columnas de leds


```
const byte FILASTECLADO = 4;
const byte COLUMNASTECLADO = 3;
```

```#const byte COLUMNASLEDS = 3;``` Aqui esta mostrando la cantidad de columnas que hay en total en el teclado matricial, en este caso tenemos 4 filas del teclado matricial


```#const byte COLUMNASLEDS = 3;``` Aqui esta mostrando la cantidad de columnas que hay en total en el teclado matricial, en este caso tenemos 3 columnas del teclado matricial

```
char teclado_matricial [FILASTECLADO][COLUMNASTECLADO] = {
  {'1', '2', '3'},
  {'4', '5', '6'},
  {'7', '8', '9'},
  {'*', '0', '#'}

};
```
```#char teclado_matricial [FILASTECLADO][COLUMNASTECLADO]```

```
int tateti[FILASLEDS][COLUMNASLEDS] = {
  {11, 12, 13},
  {14, 15, 16},
  {17, 18, 19}
};
```