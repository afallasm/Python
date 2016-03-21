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


#funciones 

#primer ejemplo
def imprime ():
    print "buenos"
    print "dias"
imprime()
imprime()
imprime()
--------------------------------------------------------------------------------------------
#segundo ejemplo
def saludo (leng):
    if leng == "es":
        print "hola"
    elif leng == "fr":
        print "bonjour"
    else:
        print "hello"
saludo("es")
saludo("fr")
saludo("cr")
----------------------------------------------------------------------------------------------
def saludo (leng):
    if leng == "es":
        print "hola"
    elif leng == "fr":
        print "bonjour"
    else:
        print "hello"
saludo(raw_input("en que idioma quiere saludar? es/fr/otro"))
-------------------------------------------------------------------------------------------------

def saludo (leng):
    if leng == "es":
        return "hola"
    elif leng == "fr":
        return "bonjour"
    else:
        return "hello"
print saludo(raw_input("en que idioma quiere saludar? es/fr/otro"))
-----------------------------------------------------------------------------------------------------
def saludo (leng):
    if leng == "es":
        return "hola"
    elif leng == "fr":
        return "bonjour"
    else:
        return "hello"
dato=saludo(raw_input("en que idioma quiere saludar? es/fr/otro"))
print dato, "allan"
print dato, "jose"
-------------------------------------------------------------------------------------------------------
funciones con ciclos

def saludo (leng):
    if leng == "es":
        return "hola"
    elif leng == "fr":
        return "bonjour"
    else:
        return "hello"
cantidad=int (raw_input("cuantas veces va a saludar?"))
cont = 0
while cont < cantidad:
    print saludo(raw_input("idioma??"))
    cont +=1
--------------------------------------------------------------------------------------------------------

#tercer ejemplo
def respuesta():
    return "hola"
print respuesta(),"andrea"
print respuesta(),"rodrigo"
-------------------------------------------------------------------------------------------------------
Ejercicio numero uno!!!!

def operacion(leng):
    num1=int (raw_input("deme el primer numero"))
    num2=int (raw_input("deme el segundo numero"))
    if leng == "suma":
        return num1+num2
    if leng == "resta":
        return num1-num2
    if leng == "multiplicacion":
        return num1*num2
    if leng == "division":
        return num1/num2
print operacion(raw_input("que desea realizar"))
print operacion(raw_input("que desea realizar"))
---------------------------------------------------------------------------------------------------------

Ejercicio numero dos!!
def calculo():
    estudiantes = 0
    if estudiantes > 35:
        return estudiantes
    elif estudiantes == 0:
        return estudiantes
    notas = 0
    if notas > 100:
        return notas
    elif notas < 0:
        return notas
contador = 0
cantidad = int (raw_input("cuantos estudiantes son?"))
    if cantidad>35 or cantidad>0:
    return cantidad
    print "la cantidad de estudiantes debe estar entre 0 y 35"

--------------------------------------------------------------------------------------------------------------
def cantidad():
    estudiantes = int (raw_input(""))
    while estudiantes<35 and estudiantes>0:
        print "la cantidad de estuadiantes es",cantidad()
        print "la cantidad de estudiantes solo puede estar entre 0 y 35"
