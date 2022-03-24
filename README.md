# EjercicioMSDOS

## Ejercicio 1

- 1

```ps1
MD APLI
MD PROG
MD VARIOS
CD APLI
MD WORD
MD ACCESS
MD EXCEL
CD WORD
MD TEXTOS
MD NOTAS
CD ..
CD EXCEL
MD TABLAS
MD INFO
CD ..
CD ..
CD PROG
MD BASIC
MD FORTRAN
MD PASCAL
```

- 2

```powershell
cd c:\Users\rivor\Documents\APLI\EXCEL\TABLAS
```

- 3

```powershell
cd c:\
```

- 4

```powershell
DIR c:\Users\rivor\Documents\PROG
```

- 5

```powershell
RD c:\Users\rivor\Documents\PASCAL
```

- 6

```powershell
CD c:\Users\rivor\Documents\VARIOS
MD c:\Users\rivor\Documents\APLI\WORD\PRACT
```

- 7

```powershell
CD c:\Users\rivor\Documents\APLI\WORD\PRACT
DIR c:\Users\rivor\Documents\APLI\EXCEL\

```

- 8

```powershell
CD ..
CD ..
DIR C:\

```

- 9

```powershell
CD c:\Users\rivor\Documents\APLI\
MD c:\Users\rivor\Documents\VARIOS\AGENDA
```

- 10

```powershell
RM c:\Users\rivor\Documents\APLI\EXCEL
```

- 11

```powershell
CD c:\Users\rivor\Documents\
MD NUEVO
```

- 12

```powershell
CD c:\Users\rivor\Documents\APLI\WORD\PRACT
DIR CD c:\Users\rivor\Documents\APLI\WORD\
```

## Ejercicio 2

- 1

Hecho, utilizando el editor disponible por defecto en Windows 10, Bloc de notas. En adelante, este tipo de operación se indicará con "OK".

- 2

```
COPY c:\Users\rivor\Documents\APLI\WORD\TEXTOS\EJER.txt c:\Users\rivor\Documents\VARIOS\AGENDA\EJER.txt
```

- 3

```
DEL c:\Users\rivor\Documents\APLI\WORD\TEXTOS\EJER.txt
```

- 4

OK.

- 5

```
CP C:\Users\rivor\Documents\VARIOS\AGENDA\EJER.txt :\Users\rivor\Documents\PROG\BASIC\EJER.txt
```

- 6

```
RENAME :\Users\rivor\Documents\VARIOS\AGENDA\EJER.txt :\Users\rivor\Documents\VARIOS\AGENDA\FICHERO.txt 
```

- 7

```
CD
MOVE VARIOS\AGENDA\FICHERO.txt PROG\BASIC
```

- 8

```
Borrado, usando Bloc de notas.
RENAME VARIOS\AGENDA\EJER.txt \VARIOS\AGENDA\NUEVO.txt
```

- 9

```
COPY PROG\BASIC\NUEVO.txt APLI\WORD\NOTAS
```

- 10

3 en BASIC, 1 en NOTAS.

## Ejercicio 3

- 1

```
RD APLI\ACCESS
MD APLI\ASTRO
```

- 2

OK.

- 3

```
CD APLI\ASTRO\CIENCIA
TREE ..\HISTORIA
```

- 4

OK.

- 5

OK.

- 6

```
COPY APLI\ASTRO\HISTORIA\DATOS1\TYCHO.txt APLI\ASTRO\CIENCIA
COPY APLI\ASTRO\HISTORIA\DATOS1\KEPLER.txt APLI\ASTRO\CIENCIA
```

- 7

```
MOVE APLI\ASTRO\CIENCIA\TYCHO.txt APLI\ASTRO\HISTORIA\DATOS2
MOVE APLI\ASTRO\CIENCIA\KEPLER.txt APLI\ASTRO\HISTORIA\DATOS1
```

- 8

```
TYPE APLI\ASTRO\HISTORIA\DATOS2\TYCHO.txt APLI\ASTRO\HISTORIA\DATOS1 > APLI\ASTRO\HISTORIA\TOTAL.txt
```

- 9

OK.

- 10

