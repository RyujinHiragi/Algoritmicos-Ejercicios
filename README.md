# Modulo 1
###  CALCULAR EDAD A PARTIR DE AÑO ACTUAL Y AÑO DE NACIMIENTO 
```
año_nacimiento = input(int('Ingrese su año de nacimiento: '))
año_actual = 2024
edad = año_actual - año_nacimiento
print('Tienes o vas a cumplir ',edad, 'años.')
```
###  CONVERTIR UNIDADES DE TEMPERATURA 
```
temp_celsius = input(int('Ingresa la temperatura en grados Celsius: '))
temp_fahrenheit = (temp_celsius * 9/5) + 32
print(temp_celsius, "grados Celsius equivalen a", temp_fahrenheit, "grados Fahrenheit")
```
### CALCULAR EL INDICE DE MASA CORPORAL 
```
peso = float(input('Ingrese su peso en kilogramos: '))
altura = float(input('Ingrese su altura en metros: '))
imc = peso / (altura ** 2)
print('Su índice de masa corporal es de:', imc)
```
### CONVERSIÓN DE VELOCIDADES 
```
velocidad_kmh = float(input('Ingrese la velocidad en kilómetros por hora: '))
velocidad_ms = velocidad_kmh * (1000 / 3600)
print('La velocidad ingresada en kilometros por hora equivale a', velocidad_ms, 'metros por segundo.')
```
### CALULAR SALARIO MENSUAL 
```
salario_diario = float(input('Ingrese el salario diario en pesos colombianos: '))
dias_trabajados = int(input('Ingrese la cantidad de días trabajados en el mes: '))
salario_mensual = salario_diario * dias_trabajados
print('El salario mensual es:', salario_mensual, 'pesos colombianos.')
```
### CALCULAR TIEMPO DE VIAJE 
```
distancia = float(input('Ingrese la distancia del viaje en kilómetros: '))
velocidad = float(input('Ingrese la velocidad promedio en kilómetros por hora: '))
tiempo = distancia / velocidad
print('El tiempo estimado de viaje es de', tiempo, 'horas.')
```
### CALCULAR TIEMPO DE DESCARGA DE UN ARCHIVO 
``` 
tamaño_archivo = float(input('Ingrese el tamaño del archivo en megabytes: '))
velocidad_descarga = float(input('Ingrese la velocidad de descarga en megabytes por segundo: '))
tiempo_descarga = tamaño_archivo / velocidad_descarga
print('El tiempo de descarga estimado es de', tiempo_descarga, 'segundos.')
```
###  CALCULAR CONSUMO DE ENERGIA 
```
consumo_por_hora = float(input('Ingrese el consumo de energía por hora en kilovatios: '))
tiempo_uso = float(input('Ingrese el tiempo de uso en horas: '))
consumo_total = consumo_por_hora * tiempo_uso
print('El consumo total de energía eléctrica es de', consumo_total, 'kilovatios.')
```
### CALCULAR EL PRESUPUESTO DE UNA FIESTA 
```
costo_por_persona = float(input('Ingrese el costo por persona en pesos colombianos: '))
invitados = int(input('Ingrese la cantidad de invitados: '))
presupuesto_total = costo_por_persona * invitados
print('El presupuesto total necesario para la fiesta es de', presupuesto_total, 'pesos colombianos.')
```
### ÁREA DE UNA HABITACIÓN 
```
largo = float(input('Ingrese el largo de la habitación en metros: '))
ancho = float(input('Ingrese el ancho de la habitación en metros: '))
altura = float(input('Ingrese la altura de la habitación en metros: '))
area_paredes = 2 * (largo + ancho) * altura
print('El área de las paredes de la habitación es de', area_paredes, 'metros cuadrados.')
```
###  VOLUMEN DE UN CONO 
```
radio = float(input('Ingrese el radio de la base del cono en metros: '))
altura = float(input('Ingrese la altura del cono en metros: '))
volumen = (1/3) * 3.1416 * radio ** 2 * altura
print('El volumen del cono es:', volumen, 'metros cúbicos.')
```
###  FACTURA TOTAL DE UN RESTAURANTE 
```
costo_comida = float(input('Ingrese el costo de la comida en pesos colombianos: '))
porcentaje_propina = float(input('Ingrese el porcentaje de propina a dejar (por ejemplo, 10 para el 10%): '))
total_pagar = costo_comida * (1 + porcentaje_propina / 100)
print('El total a pagar en el restaurante es de', total_pagar, 'pesos colombianos.')
```
### ÁREA DE UN TRIANGULO EQUILATERO CONOCIENDO UN SOLO LADO 
```
lado = float(input('Ingrese la longitud de un solo lado del triángulo equilátero en metros: '))
area_triangulo = ((3 ** 0.5) / 4) * lado ** 2
print('El área del triángulo equilátero es de', area_triangulo, 'metros cuadrados.')
```
# Modulo 2 

### El Semáforo de Tránsito 
*Condicional Simple:* Imagina un semáforo que solo cambia entre verde y rojo. Si la luz está verde, los coches avanzan. Si está roja, se detienen. Este simple control de flujo es la base de las decisiones condicionales.
```

if luz == "verde":
    print("Los coches avanzan")
else:
    print("Los coches se detienen")
```

### El Guarda Bosques y el Camino Bifurcado  
*Condicional Doble:* Piensa en un guarda bosques en una bifurcación del sendero. Si el camino de la derecha está despejado, te permite pasar por allí; de lo contrario, te dirige a la izquierda. Aquí, el programa tiene dos opciones claras basadas en una condición.
```

if camino_derecha_despejado:
    print("Pasa por el camino de la derecha")
else:
    print("Toma el camino de la izquierda")
```

### El Menú del Restaurante
*Condicional Múltiple:* En un restaurante, el chef te ofrece diferentes platos según tus preferencias: vegetariano, vegano, sin gluten, etc. Dependiendo de tu elección, el chef prepara un plato específico.
```

if preferencia == "vegetariano":
    print("Prepara un plato vegetariano")
elif preferencia == "vegano":
    print("Prepara un plato vegano")
elif preferencia == "sin gluten":
    print("Prepara un plato sin gluten")
else:
    print("Prepara un plato regular")
```
### El Detective y el Misterio 
*Condicional Anidado:* Un detective investiga un caso y, en cada etapa, debe tomar decisiones basadas en las pistas encontradas. Cada pista puede llevar a nuevas decisiones.
```

if pista == "huella digital":
    if huella_en_base_de_datos:
        print("Investiga al sospechoso")
    else:
        print("Continúa buscando más pistas")
elif pista == "cinta de seguridad":
    if cinta_clara:
        print("Analiza la cinta para identificar al sospechoso")
    else:
        print("Mejora la calidad de la cinta")
else:
    print("Busca otras pistas")
```

### El Guía Turístico en una Ciudad Desconocida  
*Condicional Simple:* Un guía turístico decide la ruta según el clima. Si llueve, lleva al grupo a museos y actividades bajo techo; si hace sol, a parques y plazas al aire libre.
```

if clima == "lluvia":
    print("Lleva al grupo a museos y actividades bajo techo")
else:
    print("Lleva al grupo a parques y plazas al aire libre")
```

### El Árbol Genealógico Familiar 
*Condicional Doble:* En un árbol genealógico, si un antepasado es de un país específico, investigas esa rama de la familia. Si no, sigues investigando en otra rama.
```

if antepasado_pais == "especifico":
    print("Investiga esa rama de la familia")
else:
    print("Sigue investigando en otra rama")
```

### El Coach de Fútbol 
*Condicional Múltiple:* Un coach de fútbol cambia su estrategia dependiendo de la situación del partido. Si va ganando, defiende; si va perdiendo, ataca; si está empatado, mantiene la posesión del balón.
```

if situacion == "ganando":
    print("Defiende")
elif situacion == "perdiendo":
    print("Ataca")
else:
    print("Mantiene la posesión del balón")

```
### El Juego de Aventura Interactiva 
*Condicional Anidado:* En un juego de aventuras, cada elección que hace el jugador lleva a diferentes escenarios. Si el jugador elige entrar en la cueva, se enfrentará a un dragón; si elige el camino del bosque, encontrará un tesoro. Dentro de la cueva, más decisiones sobre atacar o huir llevarán a nuevos resultados.
```

if eleccion == "cueva":
    if enfrentar_dragon:
        print("Lucha contra el dragón")
    else:
        print("Huye del dragón")
elif eleccion == "bosque":
    if encontrar_tesoro:
        print("Encuentra el tesoro")
    else:
        print("Sigue buscando el tesoro")
```

### La Biblioteca Inteligente 
*Condicional Simple:* Una biblioteca inteligente sugiere libros basados en tus preferencias. Si te gustan las novelas, te recomienda los últimos bestsellers de ficción; si prefieres la historia, te muestra las biografías más populares.
```

if preferencia == "novelas":
    print("Recomienda los últimos bestsellers de ficción")
else:
    print("Muestra las biografías más populares")
```

### El Sistema de Riego Automático 
*Condicional Doble:* Un sistema de riego automático revisa el pronóstico del tiempo. Si va a llover, no activa el riego; si no, riega el jardín.
```

if pronostico == "lluvia":
    print("No activa el riego")
else:
    print("Riega el jardín")

```
### La Máquina Expendedora de Snacks 
*Condicional Múltiple:* Una máquina expendedora tiene diferentes respuestas según la moneda insertada. Si insertas una moneda de $1, te ofrece una selección limitada; si insertas una moneda de $5, te permite elegir cualquier producto.
```

if moneda == 1:
    print("Ofrece una selección limitada")
elif moneda == 5:
    print("Permite elegir cualquier producto")
else:
    print("Moneda no válida")
```

### El Algoritmo de Recomendación de Películas 
*Condicional Anidado:* Un servicio de streaming recomienda películas basadas en tu historial de visualización. Si has visto muchas comedias, te sugiere comedias recientes; si dentro de las comedias viste muchas románticas, prioriza las comedias románticas.
```

if genero == "comedia":
    if tipo_comedia == "romantica":
        print("Prioriza comedias románticas")
    else:
        print("Sugiere comedias recientes")
else:
    print("Sugiere películas basadas en otros géneros")
```
# Modulo 3 

### Juego de adivinanzas numéricas: 
Escribe un programa en el que la computadora elija un número aleatorio entre un rango especificado (por ejemplo, del 1 al 100). Luego, permite que el usuario adivine el número. El programa debe indicar si el número adivinado es demasiado alto o demasiado bajo, y continuar hasta que el usuario adivine correctamente.
```

import random

numero_secreto = random.randint(1, 100)
intentos = 0

while True:
    intento = int(input("Adivina el número secreto (entre 1 y 100): "))
    intentos += 1
    
    if intento == numero_secreto:
        print("¡Correcto! ¡Has adivinado en", intentos, "intentos!")
        break
    elif intento < numero_secreto:
        print("El número secreto es mayor.")
    else:
        print("El número secreto es menor.")
```
### Generador de tarjetas de bingo: 
Crea un programa que genere tarjetas de bingo aleatorias. Puedes personalizar el tamaño del tablero y los números que pueden aparecer en él. Utiliza bucles para generar y mostrar las tarjetas de bingo.
```

import random

def generar_tarjeta():
    tarjeta = []
    for _ in range(5):
        fila = random.sample(range(1, 16), 5)
        tarjeta.append(fila)
    return tarjeta

def imprimir_tarjeta(tarjeta):
    for fila in tarjeta:
        print(fila)

n = int(input("¿Cuántas tarjetas de bingo deseas generar? "))

for i in range(n):
    print("Tarjeta", i+1, ":")
    tarjeta = generar_tarjeta()
    imprimir_tarjeta(tarjeta)
    print()
```
### Simulador de crecimiento de población: 
Escribe un programa que simule el crecimiento de una población de organismos. Define variables como la tasa de natalidad, la tasa de mortalidad y la población inicial. Utiliza un bucle para calcular el tamaño de la población en cada período de tiempo y muestra los resultados.
```

tasa_natalidad = 0.05
tasa_mortalidad = 0.02
poblacion_inicial = 1000
años = 10

poblacion = poblacion_inicial
for año in range(años):
    poblacion_nueva = poblacion * (1 + tasa_natalidad - tasa_mortalidad)
    poblacion = poblacion_nueva
    print("Población después de", año+1, "años:", round(poblacion))
```
### Calculadora de interés compuesto:  
Crea un programa que calcule el crecimiento de una inversión a lo largo del tiempo con interés compuesto. El usuario debe ingresar el monto inicial de la inversión, la tasa de interés anual y el número de años. Utiliza un bucle para calcular el saldo de la inversión en cada año y muestra los resultados.
```

monto_inicial = float(input("Ingrese el monto inicial de la inversión: "))
tasa_interes_anual = float(input("Ingrese la tasa de interés anual (%): "))
años = int(input("Ingrese el número de años: "))

tasa_interes_decimal = tasa_interes_anual / 100

for año in range(años):
    monto_final = monto_inicial * (1 + tasa_interes_decimal)
    print("Año", año + 1, "- Monto final:", round(monto_final, 2))
    monto_inicial = monto_final
Generador de patrones artísticos: Esto es un poco más complejo y depende de qué tipo de patrón deseas generar. ¿Tienes algún patrón específico en mente?
```
### Simulador de carrera de tortugas: 
```

import random

NUM_TORTUGAS = 5
META = 100

posiciones = [0] * NUM_TORTUGAS

while max(posiciones) < META:
    for i in range(NUM_TORTUGAS):
        posiciones[i] += random.randint(1, 5)

        if posiciones[i] >= META:
            print(f"¡La tortuga {i+1} ha ganado!")
            break
```
# Mudulo 4 

### Calculadora de operaciones matemáticas:
```

def suma(a, b):
    return a + b

def resta(a, b):
    return a - b

def multiplicacion(a, b):
    return a * b

def division(a, b):
    if b != 0:
        return a / b
    else:
        return "Error: división por cero"

while True:
    print("Operaciones disponibles:")
    print("1. Suma")
    print("2. Resta")
    print("3. Multiplicación")
    print("4. División")
    opcion = input("Seleccione una operación (1/2/3/4): ")
    
    if opcion in ('1', '2', '3', '4'):
        num1 = float(input("Ingrese el primer número: "))
        num2 = float(input("Ingrese el segundo número: "))
        
        if opcion == '1':
            print("Resultado:", suma(num1, num2))
        elif opcion == '2':
            print("Resultado:", resta(num1, num2))
        elif opcion == '3':
            print("Resultado:", multiplicacion(num1, num2))
        elif opcion == '4':
            print("Resultado:", division(num1, num2))
        
        continuar = input("¿Desea realizar otra operación? (s/n): ")
        if continuar.lower() != 's':
            break
    else:
        print("Opción inválida")
```

### Validador de contraseñas:
Escribe un programa que valide contraseñas según ciertos criterios (longitud mínima, presencia de caracteres especiales, números, etc.). Utiliza funciones modulares para cada criterio de validación.
```

import re

def validar_longitud(password):
    return len(password) >= 8

def validar_caracteres_especiales(password):
    return bool(re.search(r"[!@#$%^&*()]", password))

def validar_numeros(password):
    return any(char.isdigit() for char in password)

def validar_contraseña(password):
    return validar_longitud(password) and validar_caracteres_especiales(password) and validar_numeros(password)

password = input("Ingrese la contraseña a validar: ")
if validar_contraseña(password):
    print("La contraseña es válida")
else:
    print("La contraseña no cumple con los criterios de validación")
```
### Gestor de listas de tareas:
Desarrolla un programa que permita al usuario gestionar listas de tareas pendientes. Implementa funciones modulares para agregar tareas, marcar tareas como completadas, eliminar tareas y mostrar la lista de tareas.
```

tareas = []

def agregar_tarea(tarea):
    tareas.append(tarea)
    print("Tarea agregada exitosamente.")

def marcar_completada(indice):
    if 0 <= indice < len(tareas):
        tareas[indice] += " - Completada"
        print("Tarea marcada como completada.")
    else:
        print("Índice de tarea inválido.")

def eliminar_tarea(indice):
    if 0 <= indice < len(tareas):
        del tareas[indice]
        print("Tarea eliminada correctamente.")
    else:
        print("Índice de tarea inválido.")

def mostrar_tareas():
    print("Lista de tareas:")
    for i, tarea in enumerate(tareas):
        print(f"{i + 1}. {tarea}")

while True:
    print("¿Qué desea hacer?")
    print("1. Agregar tarea")
    print("2. Marcar tarea como completada")
    print("3. Eliminar tarea")
    print("4. Mostrar lista de tareas")
    print("5. Salir")
    opcion = input("Ingrese su opción: ")

    if opcion == '1':
        tarea_nueva = input("Ingrese la nueva tarea: ")
        agregar_tarea(tarea_nueva)
    elif opcion == '2':
        indice = int(input("Ingrese el índice de la tarea a marcar como completada: "))
        marcar_completada(indice - 1)
    elif opcion == '3':
        indice = int(input("Ingrese el índice de la tarea a eliminar: "))
        eliminar_tarea(indice - 1)
    elif opcion == '4':
        mostrar_tareas()
    elif opcion == '5':
        break
    else:
        print("Opción inválida. Por favor, ingrese un número del 1 al 5.")
```
### Generador de contraseñas aleatorias:
Escribe un programa que genere contraseñas aleatorias con una longitud especificada por el usuario y utilizando diferentes conjuntos de caracteres (letras mayúsculas, minúsculas, números, caracteres especiales). Implementa funciones modulares para cada conjunto de caracteres.
```

import random
import string

def generar_contraseña(longitud):
    caracteres = string.ascii_letters + string.digits + string.punctuation
    return ''.join(random.choice(caracteres) for _ in range(longitud))

longitud = int(input("Ingrese la longitud de la contraseña: "))
contraseña = generar_contraseña(longitud)
print("Contraseña generada:", contraseña)
```

### Calculadora de IMC (Índice de Masa Corporal):
```
Desarrolla un programa que calcule el Índice de Masa Corporal (IMC) de una persona a partir de su peso y altura. Utiliza una función modular para calcular el IMC y otra función para interpretar el resultado y mostrar si la persona está en un rango de peso saludable.

def calcular_imc(peso, altura):
    return peso / (altura ** 2)

def interpretar_imc(imc):
    if imc < 18.5:
        return "Bajo peso"
    elif imc < 24.9:
        return "Peso normal"
    elif imc < 29.9:
        return "Sobrepeso"
    else:
        return "Obesidad"

peso = float(input("Ingrese su peso en kg: "))
altura = float(input("Ingrese su altura en metros: "))

imc = calcular_imc(peso, altura)
print("Su IMC es:", imc)
print("Interpretación del IMC:", interpretar_imc(imc))
```

### Buscador de archivos por extensión:
Crea un programa que busque archivos en un directorio específico con una extensión dada por el usuario. Utiliza funciones modulares para manejar la búsqueda de archivos y para imprimir los resultados.
```
def buscar_archivos(directorio, extension):
    archivos_encontrados = []
    for root, dirs, files in os.walk(directorio):
        for file in files:
            if file.endswith(extension):
                archivos_encontrados.append(os.path.join(root, file))
    return archivos_encontrados

directorio = input("Ingrese el directorio a buscar: ")
extension = input("Ingrese la extensión de archivo a buscar (por ejemplo, '.txt'): ")

archivos_encontrados = buscar_archivos(directorio, extension)
print("Archivos encontrados:")
for archivo in archivos_encontrados:
    print(archivo)
```
# Calculadora de Notas

Esta es una aplicación de Flutter que calcula la nota final de una materia basada en cuatro notas con diferentes pesos.

## Descripción

La aplicación permite ingresar cuatro notas y calcula la nota final basándose en los siguientes pesos:

- Nota 1: 32.79%
- Nota 2: 32.79%
- Nota 3: 32.79%
- Nota 4: 1.64%

La nota final se ajusta para estar en el rango de 0.0 a 5.0.

## Características

- Entrada de notas a través de campos de texto.
- Validación para asegurar que las notas estén entre 0.0 y 5.0.
- Cálculo de la nota final basado en los pesos asignados.
- Visualización de la nota final calculada.

## Instalación

### Prerrequisitos

- Flutter SDK: [Instrucciones de instalación](https://flutter.dev/docs/get-started/install)
- Android Studio o Visual Studio Code con los plugins de Flutter y Dart instalados.
  
### Codigo
```
import 'package:flutter/material.dart';

void main() {
  runApp(CalculadoraNotasApp());
}

class CalculadoraNotasApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Calculadora de Notas',
      theme: ThemeData(
        primarySwatch: Colors.blue,
      ),
      home: CalculadoraNotasPage(),
    );
  }
}

class CalculadoraNotasPage extends StatefulWidget {
  @override
  _CalculadoraNotasPageState createState() => _CalculadoraNotasPageState();
}

class _CalculadoraNotasPageState extends State<CalculadoraNotasPage> {
  final TextEditingController _nota1Controller = TextEditingController();
  final TextEditingController _nota2Controller = TextEditingController();
  final TextEditingController _nota3Controller = TextEditingController();
  final TextEditingController _nota4Controller = TextEditingController();

  double _notaFinal = 0.0;

  void _calcularNotaFinal() {
    double nota1 = double.tryParse(_nota1Controller.text) ?? 0.0;
    double nota2 = double.tryParse(_nota2Controller.text) ?? 0.0;
    double nota3 = double.tryParse(_nota3Controller.text) ?? 0.0;
    double nota4 = double.tryParse(_nota4Controller.text) ?? 0.0;

    if (nota1 < 0.0) nota1 = 0.0;
    if (nota1 > 5.0) nota1 = 5.0;
    if (nota2 < 0.0) nota2 = 0.0;
    if (nota2 > 5.0) nota2 = 5.0;
    if (nota3 < 0.0) nota3 = 0.0;
    if (nota3 > 5.0) nota3 = 5.0;
    if (nota4 < 0.0) nota4 = 0.0;
    if (nota4 > 5.0) nota4 = 5.0;

    double pesoNota1 = 0.3279;
    double pesoNota2 = 0.3279;
    double pesoNota3 = 0.3279;
    double pesoNota4 = 0.0164;

    double notaFinal = (nota1 * pesoNota1) + (nota2 * pesoNota2) + (nota3 * pesoNota3) + (nota4 * pesoNota4);

    if (notaFinal < 0.0) notaFinal = 0.0;
    if (notaFinal > 5.0) notaFinal = 5.0;

    setState(() {
      _notaFinal = notaFinal;
    });
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text('Calculadora de Notas'),
      ),
      body: Padding(
        padding: EdgeInsets.all(16.0),
        child: Column(
          children: <Widget>[
            TextField(
              controller: _nota1Controller,
              decoration: InputDecoration(
                labelText: 'Nota 1',
                border: OutlineInputBorder(),
              ),
              keyboardType: TextInputType.number,
            ),
            SizedBox(height: 16.0),
            TextField(
              controller: _nota2Controller,
              decoration: InputDecoration(
                labelText: 'Nota 2',
                border: OutlineInputBorder(),
              ),
              keyboardType: TextInputType.number,
            ),
            SizedBox(height: 16.0),
            TextField(
              controller: _nota3Controller,
              decoration: InputDecoration(
                labelText: 'Nota 3',
                border: OutlineInputBorder(),
              ),
              keyboardType: TextInputType.number,
            ),
            SizedBox(height: 16.0),
            TextField(
              controller: _nota4Controller,
              decoration: InputDecoration(
                labelText: 'Nota 4',
                border: OutlineInputBorder(),
              ),
              keyboardType: TextInputType.number,
            ),
            SizedBox(height: 16.0),
            ElevatedButton(
              onPressed: _calcularNotaFinal,
              child: Text('Calcular Nota Final'),
            ),
            SizedBox(height: 16.0),
            Text(
              'Nota Final: ${_notaFinal.toStringAsFixed(2)}',
              style: TextStyle(fontSize: 24.0),
            ),
          ],
        ),
      ),
    );
  }
}
```


