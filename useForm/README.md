# useForm - Hook

Este hook permite manipular los valores de un formulario mediante un estado y un objeto. 

## Parametros

1. initialState: Es un objeto con los parametros de cada uno de los values de los elementos del formulario. 

## Estado

1. values: Objeto con los valores de cada elemento del formulario.
2. handleInputChange: Función que controla el cambio de los elementos del formulario y modifica el estado del valor de cada argumento.
3. reset: Función que restablece los valores del formulario al estado inicial.

Ejemplo de uso:
```
const initialForm = {
    name: '',
    lastName: '',
    age: 0:
    email: ''
}
const [ values, handleInputChange, reset ] = useForm(initialForm)
```