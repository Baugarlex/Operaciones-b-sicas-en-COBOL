# Operaciones básicas

El siguiente programa de COBOL le pregunta al usuario que operación desea hacer y le permite introducir números de hasta máximo 5 dígitos para ejecutar la operación con dichos números.

## Condiciones para su funcionamiento

- **En el caso de que se desee que el programa admita números de mas de 5 dígitos se puede modificar pero también se tendría que modificar los dígitos de los resultados en el número que sale entre paréntesis en la parte de** `DATA DIVISION.`
```bash
DATA DIVISION.
           FILE SECTION.
           WORKING-STORAGE SECTION.
               01 OPERACION PIC X(5).
               01 NUM1 PIC 9(5).
               01 NUM2 PIC 9(5).
               01 RESULTADO PIC Z(6).
               01 NUM3 PIC 9(5).
               01 NUM4 PIC 9(5).
               01 RESULTADOMUL PIC Z(10).
```
- **Preferiblemente personalizar los datos a los de uno mismo que vienen en** `IDENTIFICATION DIVISION.`
```bash
IDENTIFICATION DIVISION.
    PROGRAM-ID. Operaciones_Basicas.
    AUTHOR. Alex_Dan
    INSTALLATION. C:\Users\Alex\Dividiones.cbl
    DATE-WRITTEN. 04/05/2024
    DATE-COMPILED. 04/05/2024
```
- **Si se desea se puede borrar o cambiar sin ningún problema la parte que está antes de** `IDENTIFICATION DIVISION.`
```bash
******************************************************************
* Author: Alex_Dan                                               *
* Date: 04/05/2024                                               *
* Purpose: Proyecto                                              *
* Tectonics: cobc                                                *
******************************************************************
```
