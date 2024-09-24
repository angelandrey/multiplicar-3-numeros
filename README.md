# multiplicar-3-numeros
print(" ")
print("Angel Andrey Muñoz Centeno 3W")
print(" ")
#programa para multiplicar 3 digitos
#definimos la operacion deseada
def multiplicacion(a, b, c):
    return a*b*c 
n1 = float(input("ingrese el primer numero: "))
n2 = float(input("ingrese el segundo numero: "))
n3 = float(input("ingrese el tercer numero: "))
print("1. multiplicacion")
opc = int(input("ingrese la opcion deseada: "))
if opc == 1:
    print(n1, "*", n2, "*", n3, "=", multiplicacion(n1, n2, n3))
else:
    print("ERROR ingrese un numero valido. ")
    ![image](https://github.com/user-attachments/assets/606ecbf0-20e2-4306-a570-aa75b5a4ff73)
