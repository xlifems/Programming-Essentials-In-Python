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
