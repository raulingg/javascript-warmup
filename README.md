# Javascript Warm-up

Un conjunto de pequeños ejercicios totalmente dirigidos a reforzar objetivos de 
aprendizaje (OAs) del Bootcamp

## Uso de funciones (parámetros | argumentos | valor de retorno)

### Suma de 2 números

1. Crea una función `sum` la cual recibe 2 números y retorna la suma de estos.
2. Ejecuta la función `sum` pasando los valores `4` y `5`
3. Declara dos variables `a` y `b` con cualquier valor numérico, ejecuta la función
   `sum` pasando las variables `a` y `b` como argumentos.
4. Crea un función `showResult` la cual llama a la función `sum` y luego retorna
   el texto: "La suma de a + b = x", donde `x` es el resultado de invocar a `sum`
5. Refactoricemos la función `showResult` la cual ya no llama a la función `sum`, 
   sino en cambio recibe el resultado de la suma como argumento.

## Uso de bucles (for | for..in | for..of | while)

### Imprimir los nombres

```js
["Karla", "Yessica", "Margarita", "Yessenia", "Ana"]
```

1. Imprime en consola cada uno de los nombres sin usar un bucle.
2. Imprime en consola cada uno de los nombres usando un bucle `for`, `forEach`, `for of`
3. Imprime en consola los nombres del ultimo al primero.
4. Imprime en consola solo los nombres que empiezan con "Y"
5. Imprime en consola solo los nombres de longitud <= 5
6. Crea una función `getNames` que recibe un arreglo de nombres y retorna solo
   los nombres de longitud <= 5


## Manipular arrays (filter | map | sort | reduce)

### Manipulando nombres

```js
["Maria", "Yessica", "Margarita", "Nancy", "Ana"]
```

Crea una función que recibe un arreglo de nombres y hace las siguientes acciones:

1. Imprime en consola los nombres
2. Retorna un arreglo de nombres en mayúsculas.
3. Retorna un arreglo con las iniciales de los nombres
4. Retorna un arreglo de `<li>`, ejemplo: `<li>Ana</li>`
5. Retorna un arreglo solo con los nombres que empiezan con "M"
6. Retorna un arreglo con los nombres ordenamos de la A-Z
7. Retorna un arreglo con los nombres ordenamos de la Z-A
8. Retorna un arreglo con los nombres ordenamos de mayor a menor longitud.