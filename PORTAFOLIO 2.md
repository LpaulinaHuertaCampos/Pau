# <CENTER>[![Ude-C-2-L-872.png](https://i.postimg.cc/LsVkSNnf/Ude-C-2-L-872.png)](https://postimg.cc/sBvG9PPD)
# <CENTER> <span style="color:brown">FACULTAD DE INGENIERA MECANICA Y ELECTRICA</span>
## <CENTER> <span style="color:black">INGENIERIA EN COMPUTACION INTELIGENTE
### <CENTER> <span style="color:black">FUNDAMENTOS DE PROGRAMACION
### <CENTER> <span style="color:black">ALUMNO: LIDIA PAULINA HUERTA CAMPOS 
### <CENTER> <span style="color:black">PROFESOR: DR.WALTER ALEXANDER MATA LOPEZ
### <CENTER> <span style="color:black">PORTAFOLIO 2 PARCIAL
### <CENTER> <span style="color:black">1°B
ㅤㅤㅤㅤ
## <CENTER><span style="color:green">EJERCICIO 1
###### <center>CONTAR DEL 1 AL 10 Y SUMAR LOS VALORES
#### <CENTER><span style="color:green">ANÁLISIS
SE NECESITA PONER UN CONTADOR  PARA QUE NOS DE UN NUMERO MENOR O IGUAL A 10 Y SUMAR 1
#### <span style="color:green">DIAGRAMA 1 (FOR):
### <center>[![1.jpg](https://i.postimg.cc/tTShG131/1.jpg)](https://postimg.cc/5YzHw2k1)
#### <span style="color:green">DIAGRAMA 2 (WHILE):
### <center>[![2.jpg](https://i.postimg.cc/G22yKcWb/2.jpg)](https://postimg.cc/gwCjkPc7)
#### <span style="color:green">DIAGRAMA 3 (DO WHILE):
### <center>[![3.jpg](https://i.postimg.cc/Njcb4HpY/3.jpg)](https://postimg.cc/PPSmfNgF)
#### <span style="color:green">PRUEBA DE ESCRITORIO
|MSG|SALIDA|
|------|--------|
|”CONTADOR 0”|C=C+1|
#### <span style="color:green">ENTRADA
C=0
#### <span style="color:green">SALIDA
C=C+1
#### <span style="color:green">CODIGO (FOR):
<pre><code>print ("for")
for i in range(1,11):
    print(i)
xs = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
print("la suma total de los valores es...")
print(sum(xs)))</pre></code>
#### <span style="color:green">CODIGO (WHILE):
<pre><code>print ("while")
a = 1
while a <= 10:
    print(a)
    a = a + 1
xs = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
print("la suma total de los valores es...")
print(sum(xs))</pre></code>
### <span style="color:green">CODIGO (DO WHILE):
<pre><code>print ("do while")
i = 1
while i <= 10:
    print(i)
    i += 1
xs = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
print("la suma total de los valores es...")
print(sum(xs))</pre></code>


## <CENTER><span style="color:purple">EJERCICIO 2
###### <center> OBRTENER LA SUMA DE LOS PRIMEROS 5 NUMEROS PARES
#### <span style="color:purple"><CENTER>ANÁLISIS
PONER UN CONTADOR Y DESPUES IDENTIFICAR LOS NUMEROS PARES Y SUMARLOS
#### <span style="color:purple">DIAGRAMA 4 (FOR):
### <center>[![1-ER-PROBLEMA-FOR.jpg](https://i.postimg.cc/6p0ww4Fn/1-ER-PROBLEMA-FOR.jpg)](https://postimg.cc/pmp3JrWL)
#### <span style="color:purple">DIAGRAMA 5 (WHILE):
### <center>[![1-ER-PRBLEMA-WHILE.jpg](https://i.postimg.cc/VkHGjYC2/1-ER-PRBLEMA-WHILE.jpg)](https://postimg.cc/21h7YNTx)
#### <span style="color:purple">DIAGRAMA 6 (DO WHILE):
### <center>[![1-ER-PROBLEMA-DOWHILE.jpg](https://i.postimg.cc/QM2fy0Sb/1-ER-PROBLEMA-DOWHILE.jpg)](https://postimg.cc/GBjPBPW8)
#### <span style="color:purple">PRUEBA DE ESCRITORIO
|ENTRADA|SALIDA|
|------|--------|
|”s=C+S”|S|
#### <span style="color:purple">ENTRADA
s=C+S
#### <span style="color:purple">SALIDA
S
#### <span style="color:purple">CODIGO(FOR):
<pre><code> void main(List<String> args) {
  int s = 0;
  for (var i = 1; i <= 10; i++) {
    s += i;
  }
  print("La suma de los valores es: $s");
}</code></pre>
#### <span style="color:purple">CODIGO (WHILE):
<pre><code> void main(List<String> args) {
  int s = 0, c = 1;

  while (c <= 10) {
    s += c;
    c++;
  }
  print("El resultado de la suma de los valores es:$s");
}</code></pre>
#### <span style="color:purple">CODIGO (DO WHILE):
<pre><code>void main(List<String> args) {
  int s = 0, c = 1;

  do {
    s += c;
    c++;
  } while (c <= 10);
  print("El resultado de la suma de los valores es:$s");
} </code></pre>


## <CENTER><span style="color:GREEN">EJERCICIO 3
###### <center>LEER 10 NUMEROS DEL TECLADO Y PONERLOS EN UNA LISTA
#### <span style="color:GREEN"><CENTER>ANÁLISIS
SE ALMACENAN LOS NUMEROS INGRESADOS EN UNA LISTA Y SE MUESTRA
#### <span style="color:GREEN">DIAGRAMA 7 (FOR):
### <center>[![3-ER-PROBLEMA-FOR.jpg](https://i.postimg.cc/W1r8JMsq/3-ER-PROBLEMA-FOR.jpg)](https://postimg.cc/nXFBy9jn)
#### <span style="color:GREEN">DIAGRAMA 8 (WHILE):
### <center>[![3-ER-PROBLEMA-WHILE.jpg](https://i.postimg.cc/N0c4850J/3-ER-PROBLEMA-WHILE.jpg)](https://postimg.cc/nX3BpVBB)
#### <span style="color:GREEN">DIAGRAMA 9 (DO WHILE):
### <center>[![3-ER-PROBLEMA-DOWHILE.jpg](https://i.postimg.cc/C1MstXkb/3-ER-PROBLEMA-DOWHILE.jpg)](https://postimg.cc/t1f6nrrg)
#### <span style="color:GREEN">PRUEBA DE ESCRITORIO
|ENTRADA|SALIDA|
|------|--------|
|”i = 0; i <= 9; i++”|N|
#### <span style="color:GREEN">ENTRADA
i = 0; i <= 9; i++
#### <span style="color:GREEN">SALIDA
N
#### <span style="color:GREEN">CODIGO (FOR):
<pre><code>void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame 10 numeros\n ");
  stdout.write("----------\n");
  for (var i = 0; i <= 9; i++) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
    }
  }
  stdout.write("aqui esta la lista, $arra");
} </code></pre>
#### <span style="color:GREEN">CODIGO (WHILE):
<pre><code>void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  while (i <= 9) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int ner = int.parse(s);
      arra[i] = ner;
    }
    i++;
  }
  stdout.write("Tu lista es, $arra ");
} </code></pre>
#### <span style="color:GREEN">CODIGO (DO WHILE):
<pre><code> void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  do {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
      i++;
    }
  } while (i <= 9);
  stdout.write("Tu lista es $arra ");
}</code></pre>


## <CENTER><span style="color:purple">EJERCICIO 4
###### <center>ALMACENE UN CONTADOR NEGATIVO EN UN VECTOR, EL CONTEO ES DE 10 A 0.
#### <span style="color:purple"><CENTER>ANÁLISIS
PONER UNPROCESO QUE UNDIQUE EL TAMAÑO DEL VECTOR EL CUAL SERA 11
#### <span style="color:purple">DIAGRAMA 10 (FOR):
### <center>[![5-TO-PROBLEMA-FOR.jpg](https://i.postimg.cc/5NhzCy9X/5-TO-PROBLEMA-FOR.jpg)](https://postimg.cc/3dZWMKvh)
#### <span style="color:purple">DIAGRAMA 11 (WHILE):
### <center>[![5-TO-PROBLEMA-WHILE.jpg](https://i.postimg.cc/3rgNc13x/5-TO-PROBLEMA-WHILE.jpg)](https://postimg.cc/Lh8mqzqc)
#### <span style="color:purple">DIAGRAMA 12 (DO WHILE):
### <center>[![5-TO-PROBLEMA-DOWHILE.jpg](https://i.postimg.cc/Gts2LPyq/5-TO-PROBLEMA-DOWHILE.jpg)](https://postimg.cc/9wCV1717)
#### <span style="color:purple">PRUEBA DE ESCRITORIO
|ENTRADA|SALIDA|
|------|--------|
|”i = 10; i >= 0; i--”|A|
#### <span style="color:purple">ENTRADA
i = 10; i >= 0; i--
#### <span style="color:purple">SALIDA
A
#### <span style="color:purple">CODIGO(FOR):
<pre><code>void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  for (var i = 10; i >= 0; i--) {
    arr[10 - i] = i;
  }
  print(arr);
} </code></pre>
#### <span style="color:purple">CODIGO (WHILE):
<pre><code> void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  while (c >= 0) {
    arr[10 - c] = c;
    c = c - 1;
  }
  print(arr);
}</code></pre>
#### <span style="color:purple">CODIGO (DO WHILE):
<pre><code> void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  do {
    arr[10 - c] = c;
    c = c - 1;
  } while (c >= 0);
  print(arr);
}</code></pre>


## <CENTER><span style="color:GREEN">EJERCICIO 5
###### <center>ALMACENE EN UN VECTOR DE TAMAÑO 10 TODOS LOS NÚMEROS PARES CAPTURADOS HASTA COMPLETAR TODOS
#### <span style="color:GREEN"><CENTER>ANÁLISIS
ABRIR UN VECTOR Y ALMACENAR LOS NUMEROS PARES INGRESADOS Y LOS IMPARES NO PASAN
#### <span style="color:GREEN">DIAGRAMA 13 (FOR):
### <center>[![6-TO-PROBLEMA-FOR.jpg](https://i.postimg.cc/yWC3ZphD/6-TO-PROBLEMA-FOR.jpg)](https://postimg.cc/RJG0rRDm)
#### <span style="color:GREEN">DIAGRAMA 14 (WHILE):
### <center>[![6-TO-PROBLEMA-WHILE.jpg](https://i.postimg.cc/gcQ5nC5g/6-TO-PROBLEMA-WHILE.jpg)](https://postimg.cc/vD7XKNGn)
#### <span style="color:GREEN">DIAGRAMA 15 (DO WHILE):
### <center>[![6-TO-PROBLEMA-DOWHILE.jpg](https://i.postimg.cc/8zV0bhTW/6-TO-PROBLEMA-DOWHILE.jpg)](https://postimg.cc/nC02F9jc)
#### <span style="color:GREEN">PRUEBA DE ESCRITORIO
|ENTRADA|SALIDA|
|------|--------|
|”C=C+”|A|
#### <span style="color:GREEN">ENTRADA
C=C+
#### <span style="color:GREEN">SALIDA
A
#### <span style="color:GREEN">CODIGO (FOR):
<pre><code> listanumeros = []
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca otro numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca otro numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca otro numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca otro numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca otro numero: "))
listanumeros.append(numerousuario)

print(f"los numeros son {listanumeros}")

def pares(listanumeros):
    listanumeros = []


for n in listanumeros:
    if n % 2 == 0:
        print("Estos numeros son pares"+ "  " + str(n))</code></pre>
#### <span style="color:GREEN">CODIGO (WHILE):
<pre><code> listanumeros = []
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
decision = input("¿desea añadadir mas numeros?: ")

while decision == "s" or decision == "s":
    numerousuario = int(input("introdusca otro numero: "))
    listanumeros.append(numerousuario)
    decision = input("¿desea añadir otro numero?: ")


print(f"los numeros son {listanumeros}")
for n in listanumeros:
    if n % 2 == 0:
        print("Este numero de la lista es par" + str(n))
        


input("por favor, precione una tecla para salir.")</code></pre>
#### <span style="color:GREEN">CODIGO (DO WHILE):
<pre><code>print("PARES")
numero_1 = int(input("Escriba un número entero: "))
numero_2 = int(input(f"Escriba un número entero mayor o igual que {numero_1}: "))

if numero_2 < numero_1:
        print(f"¡Le he pedido un número entero mayor o igual que {numero_1}!")
else:
        for i in range(numero_1, numero_2 + 1):
            if i % 2 == 0:
                print(f"El número {i} es par.") </code></pre>
                
                
## <CENTER><span style="color:purple">EJERCICIO 6
###### <center>PREGUNTAR N Y OBTENGA LA SUMA DE LOS NUMEROS PARES
#### <span style="color:purple"><CENTER>ANÁLISIS
SE NESECITA PORNER UNA ENTRADA DE DATOS PARA OBTENER LA SUMA DE S
#### <span style="color:purple">DIAGRAMA 16 (FOR):
### <center>[![4.jpg](https://i.postimg.cc/x1r9CSMx/4.jpg)](https://postimg.cc/tYzKSwrW)
#### <span style="color:purple">DIAGRAMA 17 (WHILE):
### <center>[![5.jpg](https://i.postimg.cc/VkccwWP2/5.jpg)](https://postimg.cc/TpQsqmwc)
#### <span style="color:purple">DIAGRAMA 18 (DO WHILE):
### <center>[![6.jpg](https://i.postimg.cc/wxyvT2nB/6.jpg)](https://postimg.cc/3Wh7tX8M)
#### <span style="color:purple">PRUEBA DE ESCRITORIO
|MSG|SALIDA|
|------|--------|
|”S=S+C”|s|
#### <span style="color:purple">ENTRADA
S=S+C
#### <span style="color:purple">SALIDA
s
### <span style="color:purple">CODIGO (FOR):
<pre><code> print("CONTADOR DE PARES")
  valores = int(input("¿Cuántos valores va a introducir? "))
  if valores < 0:
      print("¡Imposible!")
  else:
      pares = 0
      for i in range(1, valores + 1):
          numero = int(input(f"Escriba el valor {i}: "))
          if numero % 2 == 0:
              pares += 1
      print(f"Ha escrito {pares} números pares.")
     

if __name__ == "__main__":
  main()ㅤ</code></pre>
#### <span style="color:purple">CODIGO (WHILE):
<pre><code>num=0

num_obtenidos=[]

rango=input('introduzca hasta que numero quiere sumar: ')

while num < int(rango):
    num+=2
    num_obtenidos.append(num)
    

listSum = sum(num_obtenidos)
print(num_obtenidos)
print( f"Suma de los números -> {listSum}")
ㅤ</code></pre>
### <span style="color:purple">CODIGO (DO WHILE):
<pre><code>print("ingrese el numero incial")
i = int(input())
print("ingrese el numero final")
f = int(input())
suma=0
print("**los numeros pares del rango**")
while i <= f:
    if i % 2 == 0:
        print(i)
        suma = suma+i
    i+=1
print("la suma de los numeros es:",suma)ㅤ</code></pre>                


## <CENTER><span style="color:green">EJERCICIO 7
###### <center>INGRESE NOMMBRES O NUMEROS Y ALMACENLOS E IMPRIMIR EN UNA LISTA
#### <CENTER><span style="color:green">ANÁLISIS
PREGUNAT LA CANTIDAD DE DATOS QUE DESEA INGRESAR PARA ALMACENARLOS
#### <span style="color:green">DIAGRAMA 19 (FOR):
### <center>[![7.jpg](https://i.postimg.cc/fWtRyCry/7.jpg)](https://postimg.cc/9z2hNdVH)
#### <span style="color:green">DIAGRAMA 20 (WHILE):
### <center>[![9.jpg](https://i.postimg.cc/QtWZ84dr/9.jpg)](https://postimg.cc/62wmzhZH)
#### <span style="color:green">DIAGRAMA 21 (DO WHILE):
### <center>[![8.jpg](https://i.postimg.cc/85qDL805/8.jpg)](https://postimg.cc/Hc4fCNHD)
#### <span style="color:green">PRUEBA DE ESCRITORIO
|MSG|SALIDA|
|------|--------|
|”ingrese n”|n|
#### <span style="color:green">ENTRADA
n numeros u nombres
#### <span style="color:green">SALIDA
lista
#### <span style="color:green">CODIGO (FOR):
<pre><code>listanumeros = []

numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)

print(f"los numeros son {listanumeros}")

listanombre = []

n=[]
x=input("ingrese nombres que desea almacenar:")
while x!="fin":
     n.append(x)
     x=input("ingrese nombre o escriba fin para terminar:")
print(n)
</pre></code>
#### <span style="color:green">CODIGO (WHILE):
<pre><code>n=[]
x=int(input("ingrese numero que desea almacenar:"))
while x!="0":
    n.append(x)
    x=input("ingrese numero o escriba fin para terminar:")
print(n)

n=[]
x=input("ingrese nombres que desea almacenar:")
while x!="fin":
     n.append(x)
     x=input("ingrese nombre o escriba fin para terminar:")
print(n)
</pre></code>
#### <span style="color:green">CODIGO (DO WHILE):
<pre><code>cantidad = int( input("ingrese la cantidad de nombres que desea almacenar:"))
nombres = []
i = 0

while i  < cantidad :
    nombre= input("ingrese el dato que decea almacenar:")
    nombres.append(nombre)
    i+=1

print("sus datos almacenados son:")

for n in nombres:
    print(n)
</pre></code>
## <CENTER><span style="color:purple">EJERCICIO 8
###### <center> capturar N números en el rango[li,ls] cantcular los numeros pares e impares y saber el promedio mayor 
#### <span style="color:purple"><CENTER>ANÁLISIS
#### Insertar primero el proceso para desglosar y preguntar el limite superior y asi hacerle con los demás seguir repitiendo poniendo una condición para sacar el numero mayor de la calificación 
#### <span style="color:purple">DIAGRAMA  (FOR):
### <center>[![ford-8.jpg](https://i.postimg.cc/28d9TQH3/ford-8.jpg)](https://postimg.cc/D8ZcwX3K)
#### <span style="color:purple">DIAGRAMA  (WHILE):
### <center>[![while-8.jpg](https://i.postimg.cc/bJQ18TSt/while-8.jpg)](https://postimg.cc/r0wDN5JV)
#### <span style="color:purple">DIAGRAMA  (DO WHILE):
### <center> [![dowhile8.jpg](https://i.postimg.cc/Sx646Y9G/dowhile8.jpg)](https://postimg.cc/k2gL94fV) 
#### <span style="color:purple">PRUEBA DE ESCRITORIO
|ENTRADA|SALIDA|
|||
|"Li, ls"|prom|
#### <span style="color:purple">ENTRADA
 Sacar numeros pares e impares saber la calificación 
#### <span style="color:purple">SALIDA
El PI es mayor que el PP y el PP es mayor que el PI
#### <span style="color:purple">CODIGO(FOR):
<pre><code> Capture n números en el rango [Li,Ls] donde: 
-Li = Limite inferior
 -Ls limite superior para li<ls y li>0
Obtenga:
 - ¿Qué promedio es mayor?
 - Cantidad de números pares y su promedio
- Cantidad de números impares y su promedio
from ast import If
import math
print("Dame Límite inferior: ")
Li = int(input())
while Li<0:
    print("El límite inferior debe ser mayor a 0")
    print("Dame Límite inferior: ")
    Li = int(input())

print("Dame límite superior: ")
Ls = int(input())
while Ls<=Li:
    print("El límite superior no puede ser menor o igual al limite inferior")
    print("Dame límite superior: ")
    Ls = int(input())

lista=[]
for x in range(8):
    valor=int(input("Ingrese un valor entero: "))
    lista.append(valor)
print(lista)

for a in lista:
    if a % 2 == 0:
        print(a)
prom1 = sum(a) / len(a)

for b in lista:
    if b % 2 != 0:
        print(b)
prom2 = sum(b) / len(b)

if(prom1>prom2):</code></pre> 
#### <span style="color:purple">CODIGO (WHILE):
<pre><code> def main():
    print("PARES E IMPARES")
    numero_1 = int(input("Escriba un número entero: "))
    numero_2 = int(input(f"Escriba un número entero mayor o igual que {numero_1}: "))

    if numero_2 < numero_1:
        print(f"¡Le he pedido un número entero mayor o igual que {numero_1}!")
    else:
        for i in range(numero_1, numero_2 + 1):
            if i % 2 == 0:
                print(f"El número {i} es par.")
            else:
                print(f"El número {i} es impar.")


if __name__ == "__main__":
    main()</code></pre>
#### <span style="color:purple">CODIGO (DO WHILE):
<pre><code>li=0
ls=0
n=0

print("dame limite inferior")
li=int(input())
while li<0:
    print("el limite inferior debe ser mayor que 0")
    li= int(input())
print("dame limite superior")
ls=int(input())
while ls>li:
    def main():
        print("PARES E IMPARES")
    numero_1 = int(input("Escriba un número que sea mas alto que su limite inferior o igual: "))
    numero_2 = int(input(f"Escriba un número entero mayor que {numero_1} y menor que su limite suerior: "))

    if numero_2 < numero_1:
        print(f"¡Le he pedido un número entero mayor que {numero_1}!")
    else:
        for i in range(numero_1, numero_2 + 1):
            if i % 2 == 0:
                print(f"El número {i} es par.")
            else:
                print(f"El número {i} es impar.")


if __name__ == "__main__":
    main() </code></pre>



## <CENTER><span style="color:green">EJERCICIO 9
###### <center> Calcule la edad de una persona.
#### <span style="color:green"><CENTER>ANÁLISIS
Dame la edad de una persona.
#### <span style="color:green">DIAGRAMA  (FOR):
### <center>[![Diagrama-E-FOR.png](https://i.postimg.cc/rs1FBC70/Diagrama-E-FOR.png)](https://postimg.cc/PvqjZZXT)
#### <span style="color:green">DIAGRAMA  (WHILE):
### <center>[![Diagrama-E-2-WHILE.png](https://i.postimg.cc/B68jVFqH/Diagrama-E-2-WHILE.png)](https://postimg.cc/cgS1KrtL)
#### <span style="color:green">DIAGRAMA  (DO WHILE):
### <center>[![Diagrama-E-DO-WHILE.png](https://i.postimg.cc/Ls55JPgw/Diagrama-E-DO-WHILE.png)](https://postimg.cc/PLGTcP4Q)
#### <span style="color:green">PRUEBA DE ESCRITORIO
|ENTRADA|SALIDA|
|------|--------|
|”año =0”|print(f'tienes {years} años')|
#### <span style="color:green">ENTRADA
año =
#### <span style="color:green">SALIDA
print(f'tienes {years} años')
#### <span style="color:green">CODIGO(FOR):
<pre><code>def main():
    año = int(input("ingresa el año en actual:"))
    cantidad = int(input("¿Cuantas personas desea ingresar?"))
    for i in range (cantidad):
        nombre = input ("Nombre de la persona:")
        nacimiento = int(input ("año de nacimiento:"))
        print (nombre,"cumple",(año - nacimiento),"años en el",año)
main() </code></pre>
#### <span style="color:green">CODIGO (WHILE):
<pre><code> from datetime import datetime, date

#fecha actual
ahora =datetime.now()

while True: 
  fecha_str = input('\n Ingrese fechade nacimiento "año/mes/dia"...: ') 
  try: 
    fecha = datetime.strptime(fecha_str, '%Y/%m/%d')
    fecha_str = fecha.strftime('%d-%m-%Y') 
    print(f'\n Tu fecha de nacimiento es: {fecha_str}')  
  except ValueError: 
    print("\n No ha ingresado una fecha correcta...") 
  else: 
    break

#dias
user_days =ahora-fecha
user_days = user_days.days

#obteniendo años
years = user_days//365
print(f'tienes {years} años')
</code></pre>
#### <span style="color:green">CODIGO (DO WHILE):
<pre><code> import os

anno_actual = int (input ('Ingresa el valor de año actual: '))
anno_de_nacimiento = int (input ('Ingresa el valor de año de nacimiento: '))
dia_actual = int (input ('Ingresa el valor de dia actual: '))
dia_de_nacimiento = int (input ('Ingresa el valor de dia de nacimiento: '))
mes_actual = int (input ('Ingresa el valor de mes actual: '))
mes_de_nacimiento = int (input ('Ingresa el valor de mes de nacimiento: '))
edad=anno_actual-anno_de_nacimiento
if mes_de_nacimiento>mes_actual or (mes_de_nacimiento==mes_actual and dia_de_nacimiento>dia_actual):
    edad=edad-1
print ('Valor de edad: ' + repr (edad))
print ()
os.system ('pause')</code></pre>

## <CENTER><span style="color:greengreen">EJERCICIO 10
###### <center> Capture unas calificaciones.
#### <span style="color:greengreen"><CENTER>ANÁLISIS
Sacar promedio de ciertas calificaiones, envase a una nota.
#### <span style="color:greengreen">DIAGRAMA  (FOR):
### <center>[![Diagrama-P-3-FOR.png](https://i.postimg.cc/x1xTVdpR/Diagrama-P-3-FOR.png)](https://postimg.cc/LJPMzmpY)
#### <span style="color:greengreen">DIAGRAMA  (WHILE):
### <center>[![Diagrama-P-WHILE.png](https://i.postimg.cc/1z8RmZLZ/Diagrama-P-WHILE.png)](https://postimg.cc/GB1nK6LM)
#### <span style="color:greengreen">DIAGRAMA  (DO WHILE):
### <center>[![Diagrama-P-2-DO-WHILE.png](https://i.postimg.cc/hGNDh5BQ/Diagrama-P-2-DO-WHILE.png)](https://postimg.cc/yJX4bnW7)
#### <span style="color:greengreen">PRUEBA DE ESCRITORIO
|ENTRADA|SALIDA|
|------|--------|
|”contador <= MATERIAS”|promedio = sumatoria / MATERIAS|
#### <span style="color:green">ENTRADA
contador <= MATERIAS
#### <span style="color:green">SALIDA
promedio = sumatoria / MATERIAS
#### <span style="color:green">CODIGO(FOR):
<pre><code> suma = 0

numeros = int(input("¿Cuántas parciales quieres promediar? "))
for x in range(numeros):
    suma += float(input("Introduce la calificacion: ") )
print("Se han introducido:", numeros, "números que en total han sumado", 
        suma, "y su promedio es:", suma/numeros)</code></pre>
#### <span style="color:green">CODIGO (WHILE):
<pre><code> 
MATERIAS = 3


nombre = input("Nombre completo: ")
grado = input("Grado: ")
grupo = input("Grupo: ")


contador = 1
sumatoria = 0
while contador <= MATERIAS:
    nombre_materia = input("Nombre de la materia {}: ".format(contador))
    calificacion = float(input("Calificación en {}: ".format(nombre_materia)))
  
    sumatoria = sumatoria + calificacion
    
    contador = contador + 1


promedio = sumatoria / MATERIAS
print("""***** Resultados *****
Alumno: {} | {} {}
*******************************
* Promedio: {}
*******************************
""".format(nombre, grupo, grado, promedio))</code></pre>
#### <span style="color:green">CODIGO (DO WHILE):
<pre><code>suma = 0
promedio=0
contador = 1
sumatoria = 0
calificacion=0

nombre = input("Nombre completo del alumno: ")
grado = input("Grado: ")
grupo = input("Grupo: ")

numeros = int(input("¿Cuántas parciales quieres promediar? "))
for x in range(numeros):
    suma += float(input("Introduce la calificacion del alumno: ") )

sumatoria = sumatoria + calificacion
    
contador = contador + 1

promedio = suma/numeros

    
print("""***** Resultados *****
Alumno: {} | {} {}
*******************************
* Promedio: {}
*******************************
""".format(nombre, grupo, grado, promedio)) </code></pre>
