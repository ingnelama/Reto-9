# Reto-9
Repositorio del reto # 9 - listas en python 

1. Desarrollar un algoritmo que calcule el promedio de un arreglo de reales.
```pseudocode
x = int
x = 0
lista = []
n = int(input("Ingrese la cantidad de elementos de la lista: "))
for i in range(n):
	elemento = float(input(f"Ingrese el elemento {i+1}: "))
	lista.append(elemento)
for i in lista:
	x += i
print("El promedio aritmetico de " + str(lista) +  " es:")
print(x / len(lista))
```

2. Desarrollar un algoritmo que calcule el producto punto de dos arreglos de números enteros (reales) de igual tamaño.
```pseudocode
print("Ingrese dos listas del mismo tamaño, el programa le retornara el producto punto")
lista_1 = []
n = int(input("Ingrese la cantidad de elementos de las listas: "))
for i in range(n):
	elemento_1 = float(input(f"Ingrese el elemento {i+1}: "))
	lista_1.append(elemento_1)
lista_2 = []
print("Ingrese ahora los elementos de la segunda lista")
for i in range(n):
	elemento_2 = float(input(f"Ingrese el elemento {i+1}: "))
	lista_2.append(elemento_2)
sumatoria = float
sumatoria = 0.0
for i in range(len(lista_1)):
	sumatoria += lista_1[i] * lista_2[i]
print("El producto punto entre " + str(lista_1) + " y " + str(lista_2) + " es: " + str(sumatoria))
	
```

3. Hacer un algoritmo que deje al final de un arreglo de números todos los ceros que aparezcan en dicho arreglo.
```pseudocode
print("Ingrese un arreglo de números enteros; el programa le retornara el arreglo pero dejando los ceros al final")
lista = []
n = int(input("Ingrese la cantidad de elementos de la listas: "))
x = int(input("Ingrese la cantidad de ceros que lleva el arreglo: "))
for i in range(n):
	elementos = float(input(f"Ingrese el elemento {i+1}: "))
	lista.append(elementos)
if lista.count(0) == 0:
	print(lista)
else:
	while lista.count(0) <= len(lista):
		lista.remove(0)
		if lista.count(0) == 0:
			break
	while len(lista) <= x:
		lista.append(0)
		if x == len(lista):
			break
	print(lista)
	
```

