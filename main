#GENERADOR DE ALIAS según largo del nombre y el apellido
import random

nombre =input("Ingrese su nombre: ").lower()
apellido = input("Ingrese su apellido: ").lower()
dni = int(input("Ingrese su dni: "))
listadepalabras = ["peregrino", "lima", "primavera", "pedazo", "golpe", "falsa", "mesa", "casamiento", "gato", "átomo", "galletita", "programa", "boton", "tinta", "señora", "pala", "pelo", "encendedor", "raton", "prima", "numero", "carta", "muro", "arabe", "jefa", "rojo", "coche", "bebe", "uñas", "manos", "serie", "medias", "abrelatas"]


def Elimina(palabra, lista):
    list(lista).remove(palabra)

    
alias = " "

if len(nombre) > 3 and len(apellido) < 10:
    for i in range(3):
        palabra = random.choice(listadepalabras[0:5])
        Elimina(palabra, listadepalabras)
        alias += palabra + "."
    print(alias[:-1])
        
elif len(nombre) < 5 and len(apellido) > 6:
    for i in range(3):
        palabra = random.choice(listadepalabras[5:9])
        Elimina(palabra, listadepalabras)
        alias += palabra + "."
    print(alias[:-1])
else:
    for i in range(3):
        palabra =random.choice(listadepalabras[9:])
        Elimina(palabra, listadepalabras)
        alias += palabra + "."
    print(alias[:-1])
