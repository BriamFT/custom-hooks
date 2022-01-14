# useCounter - Hook

Este hook establece las funciones y state necesarios para tener un contador, con su estado.

## Parametros / Estado

1. counter: Variable que contiene el estado del valor del contador (número)
2. reset: Función que establece el contador a sus valores po defecto (0)
3. increment: Función que incrementa el valor según el factor que se le envie por parametro (por defecto: 1)
4. increment: Función que decrementa el valor según el factor que se le envie por parametro (por defecto: 1)

Ejemplo de uso:
```
const {  counter, reset, increment, decrement} = useCounter(0)
```
> Nota: useCounter() //Recibe un valor por defecto