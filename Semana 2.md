Semana 2  26-08-2024


De SUSE (Sistema Operativo) deriban:
- Debion
- Fedora
- Arch

Sistemas de archivos 
- Google File System(GFS)
- Apache Hadoop HDFS(Hadoop Dstributed File System)
- PelicanHPC



MPI(Message Passing Interface)
- Apache Hadop
- Apache Spark
- OpenMP(Open Multi-Processing)

Beneficios de los SOD
- Alta disponibilidad
- Flexibilidad
- Eficiencia


Características clave de un sistema operativo distribuido
- Transparencia( es que no nos demos cuenta que estamos con varia computadoras. también es que tenga acceso )
- Recursos compartidos
- Escalabilidad
- Tolerancia a fallos( si hay un problema se puede seguir )
- Concurrencia (método que permite ejecutar dos o mas tareas simultáneamente)
- Comunicación y Coordinación.


27-08-2024
Transparencia 
- Acceso transparente: Los usuarios y aplicaciones pueden acceder a recursos (archivos, dispositivos, etc.) sin preocuparse donde están físicamente ubicados.
- Ubicación transparente: Los usuarios no necesitan conocer la ubicación física de los recursos, todo se presenta como si estuviera en un solo lugar.
- Migración transparente: Los procesos o datos pueden moverse entre diferentes nodos sin que los usuarios o aplicaciones se den cuenta.


Recursos compartidos
- Todos los recursos de un sistema operativo distribuido pueden ser compartidos entre los diferente nodos. Esto incluye archivos, dispositivos de entrada/salida, y poder de procesamiento.
- Esto maximiza la eficiencia del sistema al distribuir las cargas de trabajo y utilizar los recursos disponibles de manera óptima.

Escalabilidad
- Un sistema operativo distribuido puede escalar fácilmente añadiendo mas nodos al sistema. Esto permite manejar mayores cargas de trabajo sin sacrificar el rendimiento.
- Es ideal para entornos de crecimiento, como servidores en la nube, donde la demanda de recursos puede aumentar rápidamente.

Tolerancia a fallos: 
- Los SOD están diseñados para ser tolerantes a fallos. Si un nodo falla, el sistema puede redistribuir las tareas .

Concurrencia
- Múltiples procesos pueden ejecutarse simultáneamente en diferentes nodos, lo que mejora el rendimiento general de sistema.
- El sistema operativo gestiona la sincronización y la comunicación entre estos procesos para asegurar la coherencia y la integridad de los datos.



Comunicación y coordinación
- Los nodos en un sistema distribuido necesitan comunicarse y coordinarse entre sí. Esto se logra a través de protocolos de comunicación como RFC( Remote Procedure Call) o mensajes.
- La coordinación asegura que las tareas distribuidas se completen de manera eficiente y que los recursos no se usen o de manera ineficiente


Notas:
Protocolo: protocolo web-80
FTP-21
Existe un protocolo para conectarse a un sistema operativo distribuido.
Un puerto abierto significa que se esta enviando y recibiendo información.
Es un UDP que se usa para enviar y recibir archivos entre un usuario y un servidor a través de una red.

GPU: GPU es el acrónimo en inglés de “**U**nidad de **P**rocesamiento de **G**ráficos”. En términos generales, es un tipo de procesador que maneja y acelera la representación de gráficos (la generación de las imágenes que verá en las pantallas de las computadoras). Esto es especialmente importante para tareas informáticas como renderizado o modelado 3D y juegos de cierta categoría.


Herramientas
- MPI
- Apache Headoop
- Apache Spark



**Ley de Moore** 
La ley de Moore señala que cada dos años que pasen, se duplica el número de (transistores)que utiliza un (microprocesador).
La persona que creó dicha ley fue el ingeniero Gordon Moore. Quién fue el director de los laboratorios Fairchild Semiconductor y el cofundador de la empresa Intel.

- El transistor se trata de un dispositivo semiconductor que permite o bloquea el flujo de electrones. Capaz de modificar una señal eléctrica de salida como respuesta a una de entrada. 

- Un microprocesador es un circuito integrado central, este va ligado a un (sistema informático). Allí se llevan a cabo las operaciones lógicas y aritméticas. El microprocesador es el cerebro de un computador. Tiene como función la ejecución de programas, haciéndolo desde el sistema operativo, hasta los programas y aplicaciones de usuario.