# imcvalero
Proyecto 1: IMC

# Calculadora IMC

peso = float(input('Hola! Introduce tu peso en kilos: '))
altura = float(input('Hola! Introduce tu altura en metros: '))

calculo = peso / altura **2

int(calculo)

i = 1

while i < 2:
    if (calculo > 25): 
        print ('Oye!. Te invito a cuidar tu peso porque tu IMC es de:', calculo, '. Dale seguimiento en tu clínica.')
        i = i+1
    else: 
        print('Bien hecho!. Estás en buena forma, tu IMC es de:', calculo, '. Sigue así.')
        i = i+1
#Refelexiones: Hasta el momento he recordado varios 
