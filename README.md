# lista_de_supermercado
print(" ")

print(" ")
#("costo de cada producto a comprar")
tomates = 18000
papas = 20000
carne = 36000
queso = 35000
mortadela = 35000
huevos = 36000
import time
from datetime import date
today = date.today()
print(today)
print(" ")
print(" ")

cedula = int(input(" cedula por favor: "))
while cedula < 12996825:
    print("su cedula es incorrecta")
    cedula = int(input(" cedula por favor: "))
    print(f"Ha escrito el número {cedula}")
while cedula > 12996825:
    print("su cedula es incorrecta")
    cedula = int(input(" cedula por favor: "))
    print(f"Ha escrito el número {cedula}")
    print(" ")
if cedula == 12996825:
    print(" ")
    print("Bienvenido Sr:")
    print("david fernando pereira")
    print(f"venezolano: {cedula}")

print(" ")
print("ingrese cantidad de kilos a comprar en variedades de rublos")
# aqui seleccionaremos la cantidad de kilo por cada producto
print(" ")
kilo_de_tomate = int(input("kilo de tomate:     "))
kilo_de_papa = int(input("kilo de papa:       "))
kilo_de_carne = int(input("kilo de carne:      "))
kilo_de_queso = int(input("kilo de queso:      "))
mortadela_pollo = int(input("kilo de mortadela:  "))
carton_huevos = int(input("carton de huevos:   "))
# aqui nos dara el gasto total por cada rublo
print(" ")
print("total de gasto por cada producto")
print(" ")
a = kilo_de_tomate * tomates
print(a)
b = kilo_de_papa * papas
print(b)
c = kilo_de_carne * carne
print(c)
d = kilo_de_queso * queso
print(d)
e = mortadela_pollo * mortadela
print(e)
f = carton_huevos * huevos
print(f)
print( )
print("Total a pagar")
print( )
Total = (a + b + c + d + f, "Bolivares Fuerte")
print(Total)
