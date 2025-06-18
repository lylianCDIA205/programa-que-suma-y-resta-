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
