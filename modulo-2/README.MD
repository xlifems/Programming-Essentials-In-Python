# Módulo 2
# Tipos de datos, variables, operaciones básicas de entrada y salida, operadores básicosExternal tool

## Utilizando variables
Se tiene permitido utilizar cuantas declaraciones de variables sean necesarias para lograr el objetivo del programa, por ejemplo:

```python
var = 1
balance_cuenta = 1000.0
nombreCliente = 'John Doe'
print(var, balance_cuenta, nombreCliente)
print(var)
```

Sin embargo, no se permite utilizar una variable que no exista, (en otras palabras, una variable a la cual no se le a dado un valor).

Este ejemplo ocasionara un error:

```python
var = 1
print(Var)
```

Se ha tratado de utilizar la variable llamada <code>Var</code>, la cual no tiene ningún valor (nota: <code>var</code> y <code>Var</code> son entidades diferentes, y no tienen nada en común dentro de Python).

RECUERDA

Se puede utilizar <code> print()</code> para combinar texto con variables utilizando el operador + para mostrar cadenas con variables, por ejemplo:

```python
var = "3.7.1"
print("Versión de Python: " + var)
```

¿Puedes predecir la salida del fragmento de código?

Salida

```sh
Versión de Python: 3.7.1
```

## Asignar un valor nuevo a una variable ya existente
¿Cómo se le asigna un valor nuevo a una variable que ya ha sido creada? De la misma manera. Solo se necesita el signo de igual.

El signo de igual es de hecho un operador de asignación. Aunque esto suene un poco extraño, el operador tiene una sintaxis simple y una interpretación clara y precisa.

Asigna el valor del argumento de la derecha al de la izquierda, aún cuando el argumento de la derecha sea una expresión arbitraria compleja que involucre literales, operadores y variables definidas anteriormente.

Observa el siguiente código:

```python
var = 1
print(var)
var = var + 1
print(var)
```

El código envía dos líneas a la consola:

```python
1
2
```

La primer línea del código crea una nueva variable llamada `var` y le asigna el valor de `1`.

La declaración se lee de la siguiente manera: asigna el valor de `1` a una variable llamada `var`.

De manera mas corta: asigna `1` a `var`.

Algunos prefieren leer el código así: `var` se convierte en `1`.

La tercera línea le asigna a la misma variable un nuevo valor tomado de la variable misma, sumándole 1. Al ver algo así, un matemático probablemente protestaría, ningún valor puede ser igualado a si mismo mas uno. Esto es una contradicción. Pero Python trata el signo = no como igual a, sino como asigna un valor.

Entonces, ¿Cómo se lee esto en un programa?

Toma el valor actual de la variable var, sumale 1 y guárdalo en la variable var.

En efecto, el valor de la variable var ha sido incrementado por uno, lo cual no está relacionado con comparar la variable con otro valor.

¿Puedes predecir cuál será el resultado del siguiente fragmento de código?

```python
var = 100
var = 200 + 300
print(var)
```

Salida

`500` ¿Porque? Bueno, primero, la variable `var` es creada y se le asigna el valor de 100. Después, a la misma variable se le asigna un nuevo valor: el resultado de sumarle 200 a 300, lo cual es 500.
