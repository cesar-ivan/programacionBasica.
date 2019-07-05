# programacionBasica.
 ##PYTHON 
> python es un lenguaje de programacion creado por Guardor van Rossum a principio de los años 90, cuyo nombre fue inspirado en el grupo de comicos ingleses Monty Python es un lenguaje similar a c+, pero con una sintacxis muy limpia y que favorese un codigo legible ".


----
## comando
> 

* print()
* float()

* input()

* suma **+**

* resta **-**

* multiplicacion ** * **

* division** / o //**

* modulo ** %**

* potencia  *


----
## Anaconda prompt

1. para entar a nuestro directorio escribir **dir**
2. para entrar a la terminal escribir el comando **(Python)**.
3. Para entrar a una carpeta escribir el comando **(cd espacio despues el nombre de la capeta)**.

4. para ejecutar un programa ir a donde esta el programa escribir **(python espacio el nombre del programa)**

5. para salir de python usamos **exit()**

![captura](C:Users/Admin/ejercicios.png)


existen dos formas de ejecutar codigo en python , la cual puede ser mediante una seccion ,interactiva (linea a linea) con el interprete o bien de la forma abitual, escribiendo el codigo en un archivo de codigo fuente como bloc de notas o spieder 



----
## librerias 
>en pytohon podemos importar librerias de modulos para otro tipo de tareas que nos permite acceso a ficheros directorios.

>pero para importar librerias tenemos que importarla desde el inicio del programa 

    import numpy as np
    
    import matplotlib.pyplot as plt




----
## print()

>print nos permite mostrar texto en pantalla,el texto que queremos mostrar se escribe como argumento y encerrado en comillas ** " "**

>donde print es = comando

> mi_cadena= argumento


    mi_cadena= "tengo hambre y faltan 60 min para salir"
    
    print(mi_cadena) = tengo hambre y faltan 60 min para salir 

    tengo hambre y faltan 60 min para salir

----
## input()

>La función input() permite obtener texto escrito por teclado. Al llegar a la función, el programa se detiene esperando que se escriba algo 

>esta funcion nos permite meter numero o cnatidades pero solo enteras , no con punto decimal

    largo = float(input('incerta el largo del campo de futbol:'))
   
    ancho = float(input('incerta el ancho del campo de futbol:'))
  
    area =largo * ancho 
  
    ac = area  / 43.560
 
    print('el area del campo de futbol es de: ',ac 
    ,'acres')


----
## float()

>se usa para devolver un número de punto flotante desde un número  , tambien permite que introduscas decimales.

   
    largo = float(input('incerta el largo del campo de futbol:'))
   
    ancho = float(input('incerta el ancho del campo de futbol:'))
  
    area =largo * ancho 
  
    ac = area  / 43.560
 
    print('el area del campo de futbol es de: ',ac 
    ,'acres')

----
## operaciones aritmeticas
>todos estos signos nos permite realizar operaciones en los programas que estemos realizando 

>suma **+**

> resta **-**
 
>negacion **-**

>multiplicacion *

>exponentes **

>divivion **/**

>divivion enetera **//**

>modulo **%**



    suma r=3+2 =5
    resta r= 4-7 =-3
    negacion =-7
    muiltiplicacion =2*6 =12
    exponentes = 2**6 =64
    divivion = 3.5/2 = 1
    divivion entera =3.5/2 =1.75
    modulo 7%2 = 10

    n=int(input('numero :'))
    s=int((n*(n+1))/2)
    print('El resultado es ', s)
    

    
    cantidad = float(input('ingrese la cantidad de dinero depocitado :'))
    s = cantidad * 0.04
    por1 =cantidad+s
    print('su primer saldo ahorrado es:   ,por1,'pesos')
    a = por1 * 0.04
    por2 = por1+a
    print('su segundo saldo ahorrado es: ',por2,'pesos')
    e = por2 *0.04
    por3 = por2+e
    print('su tercer saldo ahorrado es: ',por3,'pesos')



----
## comparaciones de valores ()
>nos permiten comparar valores de las operaciones realizadas o cantidades establecidas 

>x == y     x es igual a y
 
>x =! y     x es diferente a y

>x > y      x es mayor que y
 
>x < y      x es menor que y
 
>x >= y     x es mayor igual que y
    
>x <= y     x es menor igual que y
 
    password1= input('inserte un nuevo password:')
    password2= input('confirme su password:')
    if password1 == password2:
       print('el password ah sido correcto')
    else:
       print('lo siento :(password incorrecto')


----
## if y else ()


>La sentencia If evalua basicamente una operación logica, es decir una expresión que de como resultado verdadero o false (true o false), y ejecuta la pieza de codigo siguiente siempre y cuando el resultado sea verdadero. 

>if nos permite que un programa ejecute unas instrucciones cuando se cumpla una condicion 

>else nos permite que un programa ejecute unas instrucciones cuando se cumple una condición y otras instrucciones cuando no se cumple esa condición

    numero=int(input('ingrese un numero entero :'))
    numeropar= numero%2
    
    if numeropar==0:
        print('tu numero es par')
    else:
        print('tu numero es impar')

----
## while ()
>Un bucle while permite repetir la ejecución de un grupo de instrucciones mientras se cumpla una condición (es decir, mientras la condición tenga el valor True)

>si el resultado es True se ejecuta el cuerpo del bucle. Una vez ejecutado el cuerpo del bucle, se repite el proceso (se evalúa de nuevo la condición y, si es cierta, se ejecuta de nuevo el cuerpo del bucle) una y otra vez mientras la condición sea cierta.

>si el resultado es False, el cuerpo del bucle no se ejecuta y continúa la ejecución del resto del programa
  
   
    while True :
    password= input('inserta su password:')
    if password == clave :
        print('felicidades , entraste al sistema ')
        break
    else: 
        print('password incorrecto')
        print('intenta de nuevo ')
    print('fin del programa')
    


----
##Range ()

>función devuelve una secuencia de números, comenzando desde 0 de forma predeterminada e incrementa en 1 (de forma predeterminada), y termina en un número específico.

> se utiliza para generar una secuencia de números a lo largo del tiempo. En su forma más simple, acepta un número entero y devuelve un objeto de rango



    for celcius in range (0,101,10):
       farenheiht  = celcius*1.8 +32
       print (celcius, 'gC','|', farenheiht, 'dF')

----
## if, elif ,else ()

>La estructura de control if ... permite que un programa ejecute unas instrucciones cuando se cumplan una condición. En inglés "if" significa "si" (condición).

>La condición se evalúa siempre.
Si el resultado es True se ejecuta el bloque de sentencias

>Si el resultado es False no se ejecuta el bloque de sentencias.

>La estructura de control if ... else ... permite que un programa ejecute unas instrucciones cuando se cumple una condición y otras instrucciones cuando no se cumple esa condición. En inglés "if" significa "si" (condición) y "else" significa "si no".

>utilizando else nos ahorramos escribir una condición (además, escribiendo la condición nos podemos equivocar, pero escribiendo else no).

    masa= float(input('ingrese su peso en kg:'))
    estatura = float(input('introdusca su altura en metros :'))
    imc = masa/estatura**2

    if imc < 16:
        print('tienes delgadez severa')
    elif imc >= 16 and imc  < 17 :
        print('tienes delgadez moderna')
    elif imc >= 18 and imc  < 18.5 :
        print('tienes delgadez leve ')
    elif imc >= 18.5 and imc  < 25 :
        print('tienes el IMC corecto')
    elif imc >= 25 and imc  < 30 :
        print('tienes preobesidad')
    elif imc >= 30 and imc  < 35 :
        print('tienes obesidad leve ')
    elif imc >= 35 and imc  < 40 :
        print('tienes obesidad media')
    elif imc >= 40:
        print('tienes obesidad morbida')
    else:
        print('favor de introducir datos correctos')
    print('gracias!')

----
## graficos (pyplot)
>Puede generar gráficos, histogramas, espectros de potencia, gráficos de barras, gráficos de error, diagramas de dispersión, etc., con solo unas pocas líneas de código. Para ejemplos, vea los gráficos de muestra y la galería de miniaturas .

>Para un trazado simple, el pyplotmódulo proporciona una interfaz similar a MATLAB, especialmente cuando se combina con IPython. Para el usuario avanzado, usted tiene el control total de los estilos de línea, las propiedades de fuente, las propiedades de los ejes, etc., a través de una interfaz orientada a objetos o mediante un conjunto de funciones familiares para los usuarios de MATLAB.

    
    import numpy as np
    import matplotlib.pyplot as plt

    y=int(input('que quieres graficas\n 1 seno\n 2 coseno\n 3 tangente'))

    x=np.arange(100)
    y1=np.sin(x)
    y2=np.cos(x)
    y3=np.tan(x)

    if y == 1:
       y1=plt.plot(x,y1) 
    elif y == 2:
       y2=plt.plot(x,y2) 
    elif y == 3:
       y3=plt.plot(x,y3) 
    else:
       print('ingrese los datos correctos')

    #graficando 

    plt.show()       

----
## for in ()
> Un bucle for es un bucle que repite el bloque de instrucciones un número prederminado de veces. El bloque de instrucciones que se repite se suele llamar cuerpo del bucle y cada repetición se suele llamar iteración.

    for p1 in range(4,200,5):
       p2=p1*0.60
       pf=p1-p2
    print(round(p1+.95,2),'$','|',round(p2,3),'|',round(p f+.95,3),'$')

----
## turtle  ()

>El módulo de tortuga proporciona primitivas de gráficos de tortuga, tanto de forma orientada a objetos como orientada a procedimientos. Debido a que se usa Tkinterpara los gráficos subyacentes.

>turtle nos perimite realizar figuras geoometricas o cualquier figuras dando parametros para que los relice

rafael.pensize es el grueso de la linea dibujada 

ventana.title es el titulo de la ventana 

rafael.color es el color de la tortuga 

rafael.penup es bajar la pluma y dibujar 

rafael.pendown es alzar la pluma 

ventana.bgcolor('Lightgreen') es el fondo de la ventana 

rafael.speed es la velocidad que va dibujar la tortuga 

   

     import turtle 
     a=int(input('introdusca la cantidad de circulos:'))

    ventana = turtle.Screen()
    ventana.bgcolor('Lightgreen')
    ventana.title('hola')

    rafael= turtle.Turtle()
    rafael.shape('turtle')
    rafael.color('blue')
    rafael.pensize(2)

    rafael.speed(5)

    rafael.penup()
        for pos in range(a):
        rafael.setpos(0,pos,) 
   
        rafael.pendown() 
        rafael.circle(50)

    ventana.mainloop()
        

----
# clase y objetos ()

----
## def 

>Los parámetros son datos contenidos en variables (una o más), que la función necesitará para realizar la acción. No siempre son necesarios. En nuestro caso, el parámetro self indica que la función requerirá de los atributos contenidos en la clase 

    class Coche(object):
    def __init__(self,gasolina):
        self.gasolina = gasolina
    
    def arrancar(self):
        if self.gasolina > 0:
            print('arancar')
        else:
            print('mo arranca')
    
    def conducir(self):
        if self.gasolina > 0:
            self.gasolina = self.gasolina-1
            print('quedan',self.gasolina,'litros')
        else:
            print('no se mueve')

    creacion de objetos     
    vocho = Coche(5)
    tsuru = Coche(3)

    vocho.arrancar()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()

----
## ejercicios 
 
    nombre = 'cesar ivan perez ramirez'
    calle = 'pedro m. anaya'
    colonia = 'olimpica '
    municipio = 'Naucalpan'
    estado = 'Estado de mexico'
    codigo_postal = 53575

    print(nombre + '\n' + calle + '\n' + colonia + '\n' + municipio + '\n' + estado + '\n', codigo_postal) 

----
    print('inserta tu nombre')
    nombre = input()
    print('Hola' + nombre) 
----

    l = float(input('Inserte el largo de su habitacion: '))
    an = float(input('Inserte el ancho de su habitacion: '))
    a = l*an
    print('El area de su cuarto es: ', a + 'metros cuadrados')

----

    p= float (input('inserte el numero de botellas de 1L o menos: '))
    b= float (input('inserte el numeros de botellas demas de 1L: '))
    r= p + b *2.5
    print('su pago por resiclar es:', r ,'pesos')

----
    b:float(input('ingrese el base del triangulo:'))
    al:float(input('ingrese la altura del tringulo:'))
    are:b *al
    r:are/2
    print('el area del tu triangulo es: ',r)

----

    c= float (input('cual fue el costo de la comida? '))
    i= (c*16)/100
    prp= (c*10)/100
    t=c+i+prp
    print('*****la chola'*****\n \t av. benito juarez lote.42 \n')
    print('su consumo fue de: \n \t comida: $' ,c,'\n  ' ,comida * .16')
    print ('impuesto: ', c*.16 ')

----
    n=int(input('numero :'))
    s=int((n*(n+1))/2)
    print('El resultado es ', s)

----
    w =float(input('ingrese la cantidad de widgets:'))
    g = float(input('ingrese la cantidad de gizmos:'))
    peso1= w * 0.075
    peso2= g * 0.122
    wi = peso1
    gi = peso2
    print('el peso total de su pedido es de:', wi+gi ,'kg' )

----
    cantidad = float(input('ingrese la cantidad de dinero depocitado :'))
    s = cantidad * 0.04
    por1 =cantidad+s
    print('su primer saldo ahorrado es: ',por1,'pesos')
    a = por1 * 0.04
    por2 = por1+a
    print('su segundo saldo ahorrado es: ',por2,'pesos')
    e = por2 *0.04
    por3 = por2+e
    print('su tercer saldo ahorrado es: ',por3,'pesos')

----
    import math

    a=int(input('ingresa el primer numero:'))
    b=int(input('ingresa el segundo numeero:'))
    suma=a+b
    resta=a-b
    multi=a*b
    co1=a/b
    res=a%b
    re=a**b
    print("la suma de  'a' y 'b': ", suma)
    print("la resta de 'a' y 'b': ",resta)
    print("producto de 'a' 'b'es: ",multi)
    print("el cosiente de 'a'por 'b' es:",co1)
    print("el residuo de 'a' por 'b' es:",res)
    print("el resultado de 'a' a la 'b' es: ",re)
    print("resultado de log10 'a' es: ", math.log (a, 10))
----

    c=float(input("escribe la la cantidad de gasolina en mpg: ")) 
    mpg =235.21
    r1 = mpg/c
    print("la cantidad de gasolina en litros por kilometros es: ",r1)

----
    import math
    t1=float(input('Ingrese su cordenada en grados en t1:'))
    g1=float(input('Ingrese su cordenada en grados en g1:'))
    t2=float(input('Ingrese su cordenada en gradosen t2:'))
    g2=float(input('Ingrese su cordenada en grados g2:'))
    a=t1*111.18
    b=g1*111.18
    c=t2*111.18
    d=g2*111.18
    at=(math.sin(a))*(math.sin(b))
    bt=(math.cos(a))*(math.cos(b))*(math.cos(c-d))
    ct=at+bt
    x=(6371.01)*math.acos(ct)
    print('La distancia entre ambos puntos es:',x, 'km')

----
    p=float(input('ingrese el numero de pies :'))
    pul = float(input('ingrese el numero de pulgadas :'))
    peso1= p * 12
    peso2= peso1 / 2
    peso3=pul * 2.54
    suma= peso2 + peso3

    print('el peso total de su pedido es de:', suma ,'cm')

----
    d=float(input('ingrese el numero de dias:'))
    horas=float(input('ingrese el numero de horas:'))
    m=float(input('ingrese el numero de minutos:'))
    s=float(input('ingrese el numero de segundos:'))
    di=d*86400
    ho=horas*3600
    mi=m*60
    se=s*1
    suma=di+ho+mi+se
    print('el numero de segundos total es:',suma)

----

    import time
    print(time.strftime("%I:%M:%S"))
    print(time.strftime("%d/%m/%y"))
----
    for temperatura in range (10):
       print(temperatura)



----

    numero=int(input('ingrese un numero entero :'))
    numeropar= numero%2

    if numeropar==0:
       print('tu numero es par')
    else:
       print('tu numero es impar')
----
    humanos=float(input('Indique los anos humanos :'))
    perros1=((humanos-2)*(4))+21
    perros2=humanos*10.5
    if humanos > 2:
       print('la conversion de anos humanos a perros es de ',perros1)
    elif humanos < 0:
       print('favor de ingresar los datos de forma correcta')
    else: 
       print('la conversion de anos humanos a perros es de ',perros2)
----
    for temperatura in range (10):
    print(temperatura)


----
    
    casilla=str(input('casilla? :'))

    if casilla == ('a1'):
       print('casilla negra')

    elif casilla == ('a3'):
       print('casilla negra')

    elif casilla == ('a5'):
       print('casilla negra')

    elif casilla == ('a7'):
       print('casilla negra')

    elif casilla == ('b2'):
       print('casilla negra')

    elif casilla == ('b4'):
       print('casilla negra')

    elif casilla == ('b6'):
       print('casilla negra')

    elif casilla == ('b8'):
       print('casilla negra')

    elif casilla == ('c1'):
       print('casilla negra')

    elif casilla == ('c3'):
       print('casilla negra')

    elif casilla == ('c5'):
       print('casilla negra')

    elif casilla == ('c7'):
       print('casilla negra')

    elif casilla == ('d2'):
       print('casilla negra')

    elif casilla == ('d4'):
       print('casilla negra')

    elif casilla == ('d6'):
       print('casilla negra')

    elif casilla == ('d8'):
       print('casilla negra')

    elif casilla == ('e1'):
       print('casilla negra')

    elif casilla == ('e3'):
       print('casilla negra')

    elif casilla == ('e5'):
       print('casilla negra')

    elif casilla == ('e7'):
       print('casilla negra')

    elif casilla == ('f2'):
       print('casilla negra')

    elif casilla == ('f4'):
       print('casilla negra')

    elif casilla == ('f6'):
       print('casilla negra')

    elif casilla == ('f8'):
       print('casilla negra')

    elif casilla == ('g1'):
       print('casilla negra')

    elif casilla == ('g3'):
       print('casilla negra')

    elif casilla == ('g5'):
       print('casilla negra')

    elif casilla == ('g7'):
       print('casilla negra')

    elif casilla == ('h2'):
       print('casilla negra')

    elif casilla == ('h4'):
       print('casilla negra')

    elif casilla == ('h6'):
       print('casilla negra')

    elif casilla == ('h8'):
       print('casilla negra')
    else:
       print('casilla blanca')
----
    edad= 0
    while edad < 19:
       print('tienes', edad)
       edad= edad + 1
    print('fin de programa')
----
    password1= input('inserte un nuevo password:')
    password2= input('confirme su password:')
    if password1 == password2:
       print('el password ah sido correcto')
    else:
       print('lo siento :(password incorrecto')
----
    clave ='ivand'
    password = ''

    while password != clave :
       print('password incorrecto')
       password= input('inserta su password:')

    print('felicidades , entraste al sistema ')
----
    import numpy as np
    import matplotlib.pyplot as plt

    x=np.arange(100)
    y=np.sin(x)
 
    plt.plot(x,y)
    plt.show() 
----
    for celcius in range (0,101,10):
    farenheiht  = celcius*1.8 +32
    print (celcius, 'gC','|', farenheiht, 'dF')

----





----
    num=30

    while True:
    numero = int(input('ingrese un numero del 1  al 50:'))
     if numero == 30:
        print('ganaste')
        break
     elif numero < 30:
        print('el numero es menor')
        print('intente de nuevo')
     elif numero > 30 :
        print('el numero es mayor')
        print('intente de nuevo')
     print('terminaste')

----

    import numpy as np
    import matplotlib.pyplot as plt

    y=int(input('que quieres graficas\n 1 seno\n 2 coseno\n 3 tangente'))

    x=np.arange(100)
    y1=np.sin(x)
    y2=np.cos(x)
    y3=np.tan(x)

    if y == 1:
       y1=plt.plot(x,y1) 
    elif y == 2:
       y2=plt.plot(x,y2) 
    elif y == 3:
       y3=plt.plot(x,y3) 
    else:
       print('ingrese los datos correctos')

    plt.show()    
----
    numeros = ('1','22','333','4444','55555','666666','7777777','88888888','999999999')
    for elemnt in numeros:
        print(elemnt)
----
    numerorea=50
    num=int(input('introduzca el numero para adivininar :'))
    if num<numerorea:
       print('el numero es mayor')
    elif num>numerorea:
       print('el numero es menor')
    elif num==numerorea:
       print('adivinaste el numero')
----
    for impar  in range (1, 51):
       a= (impar*2 )-1
       print(a)
----
    for numero in range (1,11,1):
    a=numero*2
    b=numero*3
    c=numero*4
    d=numero*5
    e=numero*6
    f=numero*7
    g=numero*8
    h=numero*9
    i=numero*10
    print(numero,a,b,c,d,e,f,g,h,i)
----
    edad= 0
    while edad <19:
       print('Tienes', edad)
       edad= edad+1

    print('fin de programa')
----
    class Coche(object):
    def __init__(self,gasolina):
        self.gasolina = gasolina
    
    def arrancar(self):
        if self.gasolina > 0:
            print('arancar')
        else:
            print('mo arranca')
    
    def conducir(self):
        if self.gasolina > 0:
            self.gasolina = self.gasolina-1
            print('quedan',self.gasolina,'litros')
        else:
            print('no se mueve')

     
    vocho = Coche(5)
    tsuru = Coche(3) 

    vocho.arrancar()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()
----
    class Cuenta(object):
    
    def __init__(self,monto):
        self.monto=monto 
    
    def depositar(self):
        if self.monto > 0:
            print('puede retirar ')
        else:
            print('sin fondos')
    def retirar(self):
        if self.monto > 10:
            self.monto=self.monto - 10
            print('queda',self.monto,)
        else:
            print('no puede retirar')

    a=Cuenta(100)
    b=Cuenta(50)

    b.retirar()
    a.retirar()
----
    class Triangulo(object):
    def __init__(self,angulo1,angulo2,angulo3):
        self.angulo1 = angulo1
        self.angulo2 = angulo2
        self.angulo3 = angulo3
        
    def checar(self):
        if self.angulo1 + self.angulo2 + self.angulo3 == 180:
            print('true')
        else:
            print('false')
            
    Triangulo = Triangulo(90,30,60)
    Triangulo.checar()
----
    
    def prim (primco):
       prim= ((primco  -1 )*45.00) +150.00
       if primco==1:
        
           return 150
       return prim

    primco=float(input('incerte los articulos enviados :'))
    precio=prim(primco)
    print('su tarifaes de',precio)   


----
    
    class cancion(object) :

    
    def __init__(self,letra):
        self.letra=letra
   
    def cantame(self):
       print(self.letra)

    feliz_cumple=cancion(['que cantaba el rey ','hoy por ser tu santo',' te las cantamos aqui.'])   
    
    feliz_cumple.cantame()

----
    import turtle 


    ventana = turtle.Screen()
    ventana.bgcolor('Lightgreen')
    ventana.title('hola')

    rafael= turtle.Turtle()
    rafael.shape('turtle')
    rafael.color('blue')
    rafael.pensize(2)

    rafael.speed(5)

    turtle.forward(100)
    turtle.left(90)
    turtle.forward(50)
    turtle.left(90)
    turtle.forward(100)
    turtle.left(90)
    turtle.forward(50)
    turlte.left(90)

    ventana.mainloop()

----
