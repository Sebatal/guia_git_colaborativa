# Guía colaborativa de Git
Este repositorio es un ejercicio práctico para aprender Git en parejas.
## Objetivo
Aprender y dominar Git de forma práctica para el trabajo colaborativo.


## Conceptos básicos de Git
Repositorio
Commit
Rama
Merge

## Flujo de trabajo básico
1. Editar archivos
2. git add
3. git commit
4. git push

## Ejercicio B: Preguntas de reflexión

### 1. ¿Por qué es una mala práctica trabajar directamente en main cuando se colabora?
Main es la versión estable y en producción. Si se trabaja directamente en ella genera colisiones en el código, sobreescritura sobre trabajo de otros y riesgo de quebrar la rama principal con versiones no terminadas.

### 2. ¿Qué es un conflicto de merge y por qué ocurre?
Cuando los cambios son diferentes a las líneas original. Dado que Git no decide automáticamente qué cambio es más relevante sin perder datos, por lo que solicita la aprobación manual de un usuario que defina el conflicto.

### 3. ¿Qué información debe tener un buen mensaje de commit?
Debe ser conciso, atómico y redactado en imperativo. Debe detallar qué cambio se aplicó y, si no es evidente, el motivo o contexto técnico detrás de la modificación.

### 4. ¿Qué ventaja aporta Git frente a compartir archivos por correo o Drive?
Permite la trazabilidad de cada cambio que usuario escribió tal o cual cambio y cuándo. Permite que trabajo se se realice no sobreescriba archivos o duplicar copias que tengan errores.
