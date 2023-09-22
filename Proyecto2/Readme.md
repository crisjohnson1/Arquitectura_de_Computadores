Proyecto 2 Lógica Aritmética

en este proyecto se trabajará en as siguientes chips

HalfAdder (Sumador medio):
Propósito: Realiza la suma de dos bits y produce dos salidas: la suma (bit de orden bajo) y el acarreo (bit de orden alto).
Función: Suma dos bits de entrada y produce una salida de suma y un acarreo.
Compuertas utilizadas: Dos compuertas XOR y una compuerta AND.

FullAdder (Sumador completo):
Propósito: Realiza la suma de tres bits (dos bits de entrada y un acarreo de entrada) y produce dos salidas: la suma (bit de orden bajo) y el acarreo (bit de orden alto).
Función: Suma tres bits de entrada y produce una salida de suma y un acarreo.
Compuertas utilizadas: Dos compuertas XOR, dos compuertas AND y una compuerta OR.

Add16 (Sumador de 16 bits):
Propósito: Suma dos números de 16 bits y produce un resultado de 16 bits.
Función: Realiza la suma de dos números binarios de 16 bits y produce un resultado de 16 bits.
Implementación: Utiliza 16 sumadores completos (FullAdders) en cascada.

Inc16 (Incrementador de 16 bits):
Propósito: Incrementa un número de 16 bits en uno.
Función: Suma el número de entrada de 16 bits con 1 y produce un resultado de 16 bits.
Implementación: Utiliza el chip Add16 para realizar la suma.

ALU (Unidad Aritmética y Lógica):
Propósito: Realiza operaciones aritméticas y lógicas en dos números de 16 bits según un código de operación específico.
Función: Puede realizar operaciones como suma, resta, AND, OR, y otras, según las banderas de control y el código de operación.
Implementación: Utiliza varios componentes, como sumadores, operadores lógicos y multiplexores, para realizar las operaciones deseadas.

