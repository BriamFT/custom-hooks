# useFetch - Hook

Este hook establece un canal http mediante Fetch con un URL definido, de manera asincrona con promesas. Devuelve un estado con los datos, el error y una variable boolean para saber si esta cargando los datos. 

## Parametros

1. URL: La dirección URL al recurso API que se requiere hacer la conexión para mantener un canal de peticiones y respuestas.

## Estado

1. loading: Valor booleano que define si estan cargados los datos o no.
2. error: Devuelve un valor en caso de que se haya capturado un error en la promesa.
3. data: Respuesta con los datos de la petición fetch.

Ejemplo de uso:
```
const url = https://www.ejemplo.com/api/endpoint
const {  data, loading, error } = useFetch(url)
```
