# Adivina el Número en Python

Este proyecto es un sencillo juego en Python donde la computadora genera un número aleatorio, y el objetivo del jugador es adivinarlo. El programa proporciona pistas indicando si la predicción del jugador es demasiado baja o alta, hasta que acierte el número correcto.

## Conceptos Utilizados

- **Funciones**: El juego está contenido en una función llamada `adivina_el_numero(x)`, que acepta un parámetro `x` para definir el rango del número aleatorio a adivinar.
- **Ciclo `while`**: Se utiliza un bucle `while` para seguir solicitando al jugador que adivine el número hasta que acierte.
- **Condicionales**: Se emplean estructuras `if` y `elif` para comparar la predicción del usuario con el número generado y proporcionar pistas.
- **Módulo `random`**: Se usa la función `random.randint(1, x)` para generar un número aleatorio dentro de un rango definido.
