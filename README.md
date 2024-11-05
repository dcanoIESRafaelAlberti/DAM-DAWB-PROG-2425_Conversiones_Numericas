# Conversiones numéricas.

1. Crear una función que convierta un número de base binaria a base decimal. Para ello debemos pedir un número, comprobar que es válido para la base binaria y después llamaríamos a la función convertir_binario_decimal(numero) o damos el mensaje de error correspondiente.

2. Crear una función que convierta un número de base decimal a binaria.

3. Flujo del programa:

   - Realizar un bucle en el main para realizar conversiones de números de binario a decimal o al revés hasta que se pulse ENTER con la cadena vacía.
   - Realizar una función preguntar_salir().
   - Realizar una función convertir_numero() que retornará si la conversión se ha realizado con éxito (True) o se produjo algún error. También retornará None si se introdujo la cadena vacía para que en el main podamos llamar a preguntar_salir().
   - Realizar una función limpiar_pantalla() que limpie la consola.
   - Realizar una función realizar_pausa() que hará una pausa de 2 segundos por defecto o del tiempo que le pasemos como argumento.
