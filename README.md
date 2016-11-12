# mini
Lenguaje de programación sin palabras

###Requiere Latino

Comentarios
```
// una  linea

//
Multi 
linea
//
```
Declaración de Variables
```
n = 10  // entros
r = 10.2 // reales
c = "a" // caracter
t = "Texto" // textual 
```

```
+ = Suma
- = Resta
* = Multiplicación
/ = división
% = modulo
a++ = incrementación post
--a = Decrementación pref
== = coparación de igualdad
===  = comparación de igualdad y tipo
!= = compara la desigualdad
>  = Mayor que
<  = Menor que 
>= = Mayor o igual 
=< = Menor o igual

&& = equivale al 'y' 'AND'
|| = O, OR 
 
```

 En Valores textuales
```
+ = concatenacion
. = cocatenacion
.= = concatenacion
 
```




Valores Booleanos
```
0 = falso
falso = falso
cuaquier otro simbolo es verdadero

```

```
```

escribir
```
"" 
```

ejemplo 
```
"Hola, este es mini"

```
> Si usamos las commillas simples las variables al interios son interpretadas 


Si simple
```
? condición
	acción
/ 
```
Ejemplo
```
? a > b 
	"hola"
/
```


Un si con un sino 

```

? a > b 
	"hola"
-
	"chao"
/
```
Repetir (creo que no es la mejor forma esta)

```
10,20
	"hola"
/
```

Escojer
```
::pais
  Ecuador:
	"Quito"
  Mexico:
	"DF"
  Peru:
  	"Lima"
  ?:
	"Sin capital"	
/
```
mientras

```
(a < 10)
	"escribir" . a
	a++
/
```
otra manera 
```
(i=0; i<10; i++)
	"Su valor es" . i
	
/

```
o se podria hacer 
```
(i=0; i<10; i++)
	'i'	
/
```
>Lo que esta entre comillas simples es un escribir() que interpreta las variables




Declaración de una funcion

```
[función](parametros)
	acciones
/

```

ejemplo 
```
[suma](a,b)
	a+b
/
```
LLamado de la función 
```
r = suma(a,b)

También
r = suma a,b

```

Valor enviado desde la consola
```
|a|
	'a'

	
```
Esto asigna el valor leido desde la consola a la variable ```a``` y después lo afichamos en la pantalla	


Listas

```
numeros = [1, 2, 3, 4, 5]
vacia = []

```

listas multiples o matrices
```
m = [
	[1,2,3],
	['a', 'b', 'c'],
	['alpha', 'beta', 'gamma']
     ]
```
Listas Convinadas
```
lst = [123, 'xyz', 'zara', falso]
```
















	
