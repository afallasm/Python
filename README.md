# Python
#Cicles
Este es el codigo simple donde establecemos una condicion que se debe cumplir, y en el momento que no se cumpla se saldra del ciclo e imprimira los resultados obtenidos de las operaciones.

n = int (raw_input("ingrese un numero"))

while n > 0 :
    print "n vale: ", n
    n = n-1
print "fin del ciclo"

Es posible establecer condiciones que hagan que el ciclo se termine en un determinado momento, ya sea indicando una palabra, la posicion de una o mas letras.

While cycle
while True:
    msj = raw_input("ingrese fin para terminar,")
    if msj == "fin"
        break
    print msj
print "fin del ciclo"

while True:
    msj = raw_input("ingrese fin para terminar,")
    if msj [0]=="l":
        continue
    if msj == "fin":
        break
    print msj
print "fin del ciclo"

while True:
    msj = raw_input("ingrese fin para terminar,")
    if msj [-1]=="." or msj [0]== "#":
        continue
    if msj == "fin":
        break
    print msj
print "fin del ciclo"

n = int (raw_input("ingrese un numero"))

continuar = True

while continuar:
    if n<5:
        print "salgo porque soy menor que 5"
        continuar = False
    else:
        print "n vale: ", n
    n = n-1
print "fin del ciclo"

n = int (raw_input("ingrese el numero 0"))
continuar = True
while continuar:
    if n == 100:
        print "multiplos hasta cien"
        continuar = False
    else:
        print "n vale: ,", n
    n = n+5
print "fin del ciclo"

n = int (raw_input("ingrese el numero 1"))
continuar = True
while continuar:
    if n >= 30:
        print "fin de los numeros impares"
        continuar = False
    else:
        print "n vale ,", n
    n = n+2
print "fin del ciclo"

maximo = int (raw_input("ingrese el numero al que desea llegar"))
contador = 1
n = 0
continuar = True
while continuar:
    if n >= maximo:
        print "ya hemos llegado al numero deseado"
        continuar = False
    else:
        numero = int (raw_input("ingrese un numero para sumar"))
        n = n + numero
        contador = contador + 1
print "fin del ciclo"

maximo = int (raw_input("limite a sumar"))
total = 0
cont = 1
while total<maximo:
    num= int (raw_input("deme un numero a sumar: "))
    total = total+num
    cont = cont + 1
    print "el numero", cont, "es", num
    print total
