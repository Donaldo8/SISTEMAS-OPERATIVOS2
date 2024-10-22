Adding 2 inputs

Los inputs y outputs se refieren a:
- **Input**: La información que un programa recibe del usuario o de otra fuente externa.
- **Output**: La información que el programa genera como resultado de su procesamiento.

--------------------------------------------------------------------------
1.

![[Pasted image 20241017095555.png]]

![[Pasted image 20241017095741.png]]

![[Pasted image 20241018071304.png]]
Primer ciclo.

1. **Fetching instruction**: La CPU busca la próxima instrucción.
2. **Set MAR to value held by Program Counter: 0**:El Registro de Dirección de Memoria (MAR) se configura con el valor del Contador de Programa (PC), que es 0.
3. **Increment Program Counter by 1**: El Contador de Programa (PC) se incrementa en 1.
4. **Fetch instruction from address stored in the MAR**: Se obtiene la instrucción de la dirección almacenada en el MAR (registro de dirección memoria).
5. **Fetched instruction: 901 stored in the MDR**: La instrucción `901` se almacena en el Registro de Datos de Memoria (MDR).
6. **Copy instruction from the MDR to the CIR**: La instrucción se copia del MDR al Registro de Instrucción Actual (CIR).
7. **Decoding instruction stored in CIR... INP**: La instrucción se decodifica como `INP`, que indica una instrucción de entrada.
8. **Executing Instruction**: La CPU ejecuta la instrucción.
9. **Waiting for user input**: La CPU espera una entrada del usuario.
10. **Store user input in Accumulator: 4**: La entrada del usuario (4) se almacena en el Acumulador.
    

En esta parte se procesa la instrucción de entrada y se almacena el valor (4) que ingrese en el acumulador. 

-------------------------------------------------------------------------------------------------------------
2.
![[Pasted image 20241017095914.png]]![[Pasted image 20241018070620.png]]
Segundo ciclo:

1. **Fetching instruction**: La CPU busca la próxima instrucción.
2. **Set MAR to value held by Program Counter: 1**: El Registro de Dirección de Memoria (MAR) se configura con el valor del Contador de Programa (PC), que es 1.
3. **Increment Program Counter by 1**: El Contador de Programa (PC) se incrementa en 1.
4. **Fetch instruction from address stored in the MAR**: Se obtiene la instrucción de la dirección almacenada en el MAR.
5. **Fetched instruction: 36 stored in the MDR**: La instrucción `36` se almacena en el Registro de Datos de Memoria (MDR).
6. **Copy instruction from the MDR to the CIR**: La instrucción se copia desde el MDR al Registro de Instrucción Actual (CIR).
7. **Decoding instruction stored in CIR... STA**: La instrucción se decodifica como `STA`, que significa almacenar.
8. **Executing Instruction**: La CPU ejecuta la instrucción.
9. **Set MAR to the operand of the current instruction: 6**: El MAR se configura con el operando de la instrucción actual, que es 6.
10. **Set MDR to the value held in the Accumulator: 4**: El MDR se configura con el valor almacenado en el Acumulador, que es 4.
11. **Store MDR value 4 at the memory location held in the MAR: 6**: El valor del MDR (4) se almacena en la ubicación de memoria 6.

En esta parte se almacena el valor del Acumulador en una ubicación específica de la memoria. 

--------------------------------------------------------------------------
3.
![[Pasted image 20241017100131.png]]![[Pasted image 20241017100202.png]]
![[Pasted image 20241018071652.png]]
Tercer ciclo.

1. **Fetching instruction**: La CPU busca la próxima instrucción.
2. **Set MAR to value held by Program Counter: 2**: El Registro de Dirección de Memoria (MAR) se configura con el valor del Contador de Programa (PC), que es 2.
3. **Increment Program Counter by 1**: El Contador de Programa (PC) se incrementa en 1.
4. **Fetch instruction from address stored in the MAR**: Se obtiene la instrucción de la dirección almacenada en el MAR.
5. **Fetched instruction: 901 stored in the MDR**: La instrucción `901` se almacena en el Registro de Datos de Memoria (MDR).
6. **Copy instruction from the MDR to the CIR**: La instrucción se copia desde el MDR al Registro de Instrucción Actual (CIR).
7. **Decoding instruction stored in CIR... INP**: La instrucción se decodifica como `INP`, que es una instrucción de entrada.
8. **Executing Instruction**: La CPU ejecuta la instrucción.
9. **Waiting for user input**: La CPU espera una entrada del usuario.
10. **Store user input in Accumulator: 3**: La entrada del usuario (3) se almacena en el Acumulador.
    

En esta parte se procesa una instrucción de entrada y se almacena el segundo valor ingresado en el Acumulador. 

--------------------------------------------------------------------------
4.
![[Pasted image 20241017100328.png]]
![[Pasted image 20241018071757.png]]
Cuarto ciclo.

1. **Fetching instruction**: La CPU está buscando la próxima instrucción.
2. **Set MAR to value held by Program Counter: 3**: El Registro de Dirección de Memoria (MAR) se establece con el valor del Contador de Programa (PC), que es 3.
3. **Increment Program Counter by 1**: El Contador de Programa (PC) se incrementa en 1 para preparar la siguiente instrucción.
4. **Fetch instruction from address stored in the MAR**: Se obtiene la instrucción de la dirección almacenada en el MAR.
5. **Fetched instruction: 16 stored in the MDR**: La instrucción `16` se almacena en el Registro de Datos de Memoria (MDR).
6. **Copy instruction from the MDR to the CIR**: La instrucción se copia del MDR al Registro de Instrucción Actual (CIR).
7. **Decoding instruction stored in CIR... ADD**: La instrucción se decodifica como `ADD`, que significa que se realizará una suma.
8. **Executing Instruction**: La CPU ejecuta la instrucción.
9. **Set MAR to the operand of the current instruction: 6**: El MAR se configura con el operando de la instrucción actual, que es 6.
10. **Fetch data at the location held by the MAR and store it in the MDR: 4**: Se obtiene el dato en la dirección 6 (valor 4) y se almacena en el MDR.
11. **Add MDR value to the Accumulator and store the result in the Accumulator: 3+4=7**: Se suma el valor del MDR (4) al valor del Acumulador (3), resultando en 7, que se almacena en el Acumulador.
    
Se procesa la instrucción de suma, obteniendo el valor desde la memoria y actualizando el Acumulador con el resultado. 

-------------------------------------------------------------------------------------------------------------
5.
![[Pasted image 20241017100503.png]]
![[Pasted image 20241018071909.png]]
Quinto ciclo.

1. **Fetching instruction**: La CPU busca la próxima instrucción.
2. **Set MAR to value held by Program Counter: 4**: El Registro de Dirección de Memoria (MAR) se establece con el valor del Contador de Programa (PC), que es 4.
3. **Increment Program Counter by 1**: El Contador de Programa (PC) se incrementa en 1 para apuntar a la siguiente instrucción.
4. **Fetch instruction from address stored in the MAR**: Se obtiene la instrucción desde la dirección almacenada en el MAR.
5. **Fetched instruction: 902 stored in the MDR**: La instrucción `902` se almacena en el Registro de Datos de Memoria (MDR).
6. **Copy instruction from the MDR to the CIR**: La instrucción se copia del MDR al Registro de Instrucción Actual (CIR).
7. **Decoding instruction stored in CIR... OUT**: La instrucción se decodifica como `OUT`, que indica una instrucción de salida.
8. **Executing Instruction**: La CPU ejecuta la instrucción.
9. **Output value held in the Accumulator: 7**: El valor contenido en el Acumulador (7) se envía a la salida.
    
En esta parte se saca el valor del Acumulador (7) y lo muestra como salida. 

--------------------------------------------------------------------------
6.
![[Pasted image 20241017100636.png]]
![[Pasted image 20241018072043.png]]Sexto ciclo.

1. **Fetching instruction**: La CPU busca la próxima instrucción.
2. **Set MAR to value held by Program Counter: 5**: El Registro de Dirección de Memoria (MAR) se establece con el valor del Contador de Programa (PC), que es 5.
3. **Increment Program Counter by 1**: El Contador de Programa (PC) se incrementa en 1 para apuntar a la siguiente instrucción.
4. **Fetch instruction from address stored in the MAR**: Se obtiene la instrucción de la dirección almacenada en el MAR.
5. **Fetched instruction: 000 stored in the MDR**: La instrucción `000` se almacena en el Registro de Datos de Memoria (MDR).
6. **Copy instruction from the MDR to the CIR**: La instrucción se copia del MDR al Registro de Instrucción Actual (CIR).
7. **Decoding instruction stored in CIR... HLT**: La instrucción se decodifica como `HLT`, que indica una instrucción de parada.
8. **Executing Instruction**: La CPU ejecuta la instrucción.
9. **Program stopped**: El programa se detiene.
    
En esta parte el proceso finaliza su ejecución al encontrar la instrucción de parada (`HLT`).  y me muestra el mensaje de que mi programa ha sido ejecutado en 6 ciclos FDE (Fetch-Decode-Execute).

--------------------------------------------------------------------------
