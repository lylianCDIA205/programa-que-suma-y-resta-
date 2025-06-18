# programa-que-suma-y-resta-
programa de lylian y evelin
def suma(a, b):
    return a + b

def resta(a, b):
    return a - b

def main():
    print("Programa que suma y resta dos números")
    num1 = float(input("Introduce el primer número: "))
    num2 = float(input("Introduce el segundo número: "))

    print(f"La suma de {num1} y {num2} es: {suma(num1, num2)}")
    print(f"La resta de {num1} y {num2} es: {resta(num1, num2)}")

if _name_ == "_main_":
    main()
def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "Error: No se puede dividir entre cero"
    return a / b

def main():
    print("Calculadora de multiplicación y división")
    num1 = float(input("Introduce el primer número: "))
    num2 = float(input("Introduce el segundo número: "))

    print(f"{num1} x {num2} = {multiplicar(num1, num2)}")
    resultado_div = dividir(num1, num2)
    print(f"{num1} ÷ {num2} = {resultado_div}")

if __name__ == "__main__":
    main()
