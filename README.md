<h1 align="center">	Ejercicios  de la entrega individual del bro </h1>

<h2>Repositorio:</h2>

Este es el link del [repositorio]https://github.com/Barroso03/ejercicios-entrega-individual-del-bro
***
## EJERCICIO 8:
Es un ejercicio de aplicar impuestos e intereses

**APARTADO 1**
```
algoritmo TII

Entrada
p = preciosinimpuestos
i = IVA
c = costefinal

Precondición
p > 0
i > 0
c > 0

Realización
si p > 0:
  c = p + (p x i)
si no:
  vuelve

Poscondición
c = p + (p x i)

fin algoritmo TII
```

**APARTADO 2**
```
algoritmo interes

Entrada
c = capitalinvertido
i = interes
t = tiempo
a = importegenerado

Precondición
c > 0
i > 0
t > 0
a > 0

Realizacion
si c > 0:
  a = c x i x t
si no: 
  vuelve

Poscondicion
a = c x i x t

fin algoritmo interes  
```
***
## EJERCICO 9:
Es un ejercicio que calcula la media aritmetica y la media ponderada

**APARTADO 1**
```
algoritmo media

Entrada
a = primer numero
b = segundo numero
c = tercer numero
r = resultado
Precondición
a, b, c: REAL

Realización
r = (a + b + c) / 3
Poscondición
r = (a + b + c) / 3: REAL

fin algoritmo media
```

**APARTADO 2**
```
algoritmo mediaponderada

Entrada
a = primer numero
b = segundo numero
c = tercer numero
y = coeficientes de ponderacion
r = resultado
n1, n2, n3 = coeficientes de ponderacion / 100
Precondición
a, b, c: REAL
0 < n1, n2, n3 < 1
Realización
r = (a x n1) + (b x n2) + (c x n3)
Poscondición
r = (a x n1) + (b x n2) + (c x n3): REAL

fin algoritmo mediaponderada
```
***
## EJERCICIO 10
El ejercicio trata de calcular el área de un triángulo
```
algoritmo areatriangulo

Entrada:
l = ladodeltriángulo
h = alturadeltriángulo
a = area
Precondición:
l > 0
h > 0
a > 0

Realización:
si l y a > 0:
  a = (l x h) / 2
Poscondición
a = (l x h) / 2: REAL

fin algoritmo areatriangulo
```
**APARTADO 2**
Si se puede utilizar este algoritmo para un triángulo rectángulo
***

## EJERCICIO 11


## EJERCICIO 12














