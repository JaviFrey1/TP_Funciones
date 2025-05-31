import math

# Ej 1. 
def imprimir_hola_mundo():
    print("Hola Mundo!")

# Ej 2.
def saludar_usuario(nombre):
    return f"Hola {nombre}!"

# Ej 3.
def informacion_personal(nombre, apellido, edad, residencia):
    print(f"Soy {nombre} {apellido}, tengo {edad} años y vivo en {residencia}.")

# Ej 4.
def calcular_area_circulo(radio):
    return math.pi * radio ** 2

def calcular_perimetro_circulo(radio):
    return 2 * math.pi * radio

# Ej 5.
def segundos_a_horas(segundos):
    return segundos / 3600

# Ej 6.
def tabla_multiplicar(numero):
    for i in range(1, 11):
        print(f"{numero} x {i} = {numero * i}")

# Ej 7.
def operaciones_basicas(a, b):
    suma = a + b
    resta = a - b
    multiplicacion = a * b
    division = a / b if b != 0 else "Error: división por cero"
    return suma, resta, multiplicacion, division

# Ej 8.
def calcular_imc(peso, altura):
    return peso / (altura ** 2)

# Ej 9.
def celsius_a_fahrenheit(celsius):
    return (celsius * 9 / 5) + 32

# Ej 10.
def calcular_promedio(a, b, c):
    return (a + b + c) / 3


if __name__ == "__main__":
    # Ejercicio 1
    imprimir_hola_mundo()

    # Ejercicio 2
    nombre = input("Ingresa tu nombre: ")
    print(saludar_usuario(nombre))

    # Ejercicio 3
    nombre = input("Nombre: ")
    apellido = input("Apellido: ")
    edad = input("Edad: ")
    residencia = input("Lugar de residencia: ")
    informacion_personal(nombre, apellido, edad, residencia)

    # Ejercicio 4
    radio = float(input("Ingresa el radio de un círculo: "))
    print(f"Área: {calcular_area_circulo(radio):.2f}")
    print(f"Perímetro: {calcular_perimetro_circulo(radio):.2f}")

    # Ejercicio 5
    segundos = int(input("Ingresa la cantidad de segundos: "))
    print(f"Equivale a {segundos_a_horas(segundos):.2f} horas")

    # Ejercicio 6
    numero = int(input("Ingresa un número para ver su tabla de multiplicar: "))
    tabla_multiplicar(numero)

    # Ejercicio 7
    a = float(input("Ingresa el primer número: "))
    b = float(input("Ingresa el segundo número: "))
    suma, resta, multi, div = operaciones_basicas(a, b)
    print(f"Suma: {suma}, Resta: {resta}, Multiplicación: {multi}, División: {div}")

    # Ejercicio 8
    peso = float(input("Ingrese su peso (kg): "))
    altura = float(input("Ingrese su altura (m): "))
    print(f"Tu IMC es: {calcular_imc(peso, altura):.2f}")

    # Ejercicio 9
    celsius = float(input("Ingresa la temperatura en °C: "))
    print(f"Equivale a {celsius_a_fahrenheit(celsius):.2f} °F")

    # Ejercicio 10
    n1 = float(input("Primer número: "))
    n2 = float(input("Segundo número: "))
    n3 = float(input("Tercer número: "))
    print(f"El promedio es: {calcular_promedio(n1, n2, n3):.2f}")
