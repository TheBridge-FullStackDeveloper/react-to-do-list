# To do List 馃搫

En este ejercicio iremos creando una lista de tareas con REACT

![ezgif com-gif-maker](https://user-images.githubusercontent.com/33903092/131694503-8ca93b45-ff80-4291-9bc6-b590c3c764c1.gif)

## Primera iteraci贸n

Instalar las dependencias con `npm i`

Para arrancar el servidor:

```sh
npm run dev
```

## Segunda iteraci贸n

Crear un input para poder a帽adir las tareas a la lista.

馃挕 Pista: puedes utilizar el evento `onKeyDown` o a帽adir un bot贸n y utilizar el evento `onClick`

## Tercera iteraci贸n

Crear la funci贸n que actualize el estado al momento de pulsar `Enter` o con al hacer click en un bot贸n.

馃挕 Pista: En el estado tendremos las diferentes tareas de la lista, por eso el estado puede ser un array

## Cuarta iteraci贸n

Dibujar en el DOM la lista de tareas.

## Bonus

- A帽ade funcionalidad para poder tachar o eliminar las tareas.
馃挕 Pista: Para esta iteraci贸n el estado deber铆a ser un array de objectos, podr铆a ser algo as铆:

```js
{
  description: 'Tarea',
  isDone: false,
  _id: 1,
}
```
- Implementa la funcionalidad para remover el elemento de la lista

- Implementa las dos opciones para a帽adir los elementos, con la tecla `Enter` y con el click de un bot贸n

- Divide el c贸digo en componentes