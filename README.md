# BumperCar
Proyecto de construcción de un robot autonomo, cuya función es detectar un choque y esquivar el obstaculo que lo produjo.
Para este proyecto se ha usado una PIC de la marca Microchip, en concreto el microcontrolador PIC16F15376.
EL lenguaje usado para programar la pic es el lenguje ensamblador, en el usamos las rutina de interrupción de los modulos, 
TMR0, TMR1, Perifericos,CCPM1 y el modulo conversor "analogico/digital"(ADCON), para la realizar la toma de decisiones y en base a estas elegir en que modo operar.
EL modo de funcionamiento es en el siguiente orden:
  -Movimiento rectilineo hacia delante
  -Detección de choque
  -Modo "esquivar", el cual hace que el robot se mueva hacia atras mientras que gira las ruedas delanteras(usando un Ackermann)
  -Vuelta a condiciones iniciales de movimiento tras la esquiva
  
TOdo lo referente al proyecto esta reflejado mas detalladamente en los archivos adjuntos, en los que se explicar el software, el Harware y demas aspectos necesarios 
para entender como funciona y el porque de usar cada elemento.
