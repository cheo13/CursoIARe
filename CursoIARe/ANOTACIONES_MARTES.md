
PYTHON
Lenguaje de programacion...
Google Colab: Se uso para la ejecución de código Python de manera instantánea usan el servicio de Google, creamos las primeras líneas de código en Python.
			         print('Hello world')
El uso de funciones y formas de concatenación.
Funciones de orden superior
Listas---
Son secuencias ordenadas de valores que pueden ser modificadas e indexadas
OBJETOS LITERALES.
STRINGS Y DICCIONARIOS.
-----CONTEXTOO----
LIBRERIAS EXTERNAS....
En velocidad de ejecución Javascript es mas rapido que Python.
FUNCIONES Y AYUDAS EN PYTHON:
Una función es un conjunto de lineas de codigo que realizan una tarea especifica y pueden tomar "Argumentos" para diferentes "Parametros" que modifiquen su funcionamiento y los datos de salida.

ARGUMENTOS Y PARAMETROS: 
Se pueden convertir en argumentos cuando interviene una llamada de los valores.
SENTENCIAS: 
La sentencia "return" ayuda a que las funciones se puedan comunicar con el exterior.
### **Notas**
Si la definición de una función incluye parámetros, debe proporcionar el mismo número de parámetros cuando llame a la función.

-Se realizo un ejercicio sobre un juego de oroscopo para dar un mensaje aleatorio segun el signo de la persona.
horoscope = ['Hoy es un buen día para tomar decisiones importantes.',

    'Vas a recibir una sorpresa inesperada en el amor.',

    'Es un buen momento para planificar un viaje.',

    'Te sentirás lleno de energía y motivación.',

    'Ten cuidado con los gastos excesivos hoy.',

    'Aprovecha el día para relajarte y cuidar de ti mismo.',

    'Tendrás éxito en tus proyectos laborales.',

    'Recibirás noticias positivas que te alegrarán el día.',

    'Es un buen momento para aprender algo nuevo.',

    'Tu intuición te guiará en la toma de decisiones.',

    'Evita los conflictos y busca la armonía en tus relaciones.',

    'Tu creatividad estará en su máximo esplendor.']

  

zodiac = ['Aries', 'Tauro', 'Géminis', 'Cáncer', 'Leo', 'Virgo',

          'Libra', 'Escorpio', 'Sagitario', 'Capricornio', 'Acuario', 'Piscis']

  

def obtener_horoscopo(signo):

    return horoscope[zodiac.index(signo)]

  

def main():

    print("Bienvenido/a al horóscopo del día.")

    name_sig = input("Ingresa tu signo del zodiaco: ")

  

    if name_sig.capitalize() in zodiac:

        horoscopo = obtener_horoscopo(name_sig.capitalize())

        print(f"\nHoróscopo para {name_sig.capitalize()}:")

        print(horoscopo)

    else:

        print("Signo del zodiaco no reconocido. Ingresa un signo válido.")

  

if __name__ == "__main__":

    main()