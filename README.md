import time
import os

def limpiar_pantalla():
    os.system('cls' if os.name == 'nt' else 'clear')

def imprimir_mensaje(mensaje):
    for letra in mensaje:
        print(letra, end='', flush=True)
        time.sleep(0.1)
    print()

def main():
    limpiar_pantalla()
    mensaje = "Te Amo Alma"
    imprimir_mensaje(mensaje)
    time.sleep(1)
    limpiar_pantalla()
    print("💖 " + mensaje + " 💖")
    time.sleep(1)
    limpiar_pantalla()
    print("😘 " + mensaje + " 😘")
    time.sleep(1)
    limpiar_pantalla()
    print("💗💗💗💗💗")
    print("💗 T 💗 E 💗 A 💗 M 💗 O 💗")
    print("💗   💗 A 💗 L 💗 M 💗 A 💗")
    print("💗💗💗💗💗")

if __name__ == "__main__":
    main()
