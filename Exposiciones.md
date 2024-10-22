                                                      13-09-2024 y 23-09-2024
***APACHE SPARK***
Es una plataforma de procesamiento de datos de código abierto, diseñada para crear cálculos ultrarrápidos y a gran escala.

Sirve para aplicaciones de aprendizaje y para la inteligencia artificial.

Funciona a través del modelo maestro-esclavo. El maestro coordina el clúster.

Se aplica en:  
- Maneja conjuntos de gran escala.
- Su arquitectura es jerárquica maestro/esclavo.

Spark Driver es el nodo maestro que controla el administrador,

Sus beneficios son:
- Acelerar el desarrollo de aplicaciones.
- Innova mas rápido.
- Gestiona con facilidad.
- Procesa mas rápido.

 Es 100 veces mas rápido que hadoop
- Apache Spark MLIib
- Spark Graphx


- Velocidad, realiza operaciones mas rápidas en la memoria y reduce tiempos.
- Escalabilidad, Tiene funcionamiento de manera horizontal.
La escalabilidad horizontal se basa en la idea de **distribuir la carga de trabajo entre múltiples servidores o nodos en lugar de depender de uno solo**. Esto se logra mediante el uso de tecnologías como la virtualización, los sistemas distribuidos y los algoritmos de equilibrio de carga.

- Facilidad de uso, Mejor manejo de interfaz amigable.
- Flexibilidad, Permite alta gama de fuentes de
- Amplia comunidad en soporte


Ventajas:
- Tiene una gran comunidad, popularidad ya que permite aumentar la velocidad de los datos.

Desventajas:
- Curva de aprendizaje.
- Consumo de recursos.
- Complejidad en la configuración.
- Rendimiento afectado por la red.


Apache es flexible, veloz, y maneja todo en tiempo real.

Un **clúster** en Apache Spark y Apache Kafka se refiere a un conjunto de servidores que trabajan juntos para procesar y gestionar grandes volúmenes de datos de manera eficiente.
- Clúster de Spark: Un clúster de Apache Spark está compuesto por un nodo maestro y varios nodos trabajadores. El nodo maestro gestiona el clúster y distribuye las tareas a los nodos trabajadores, que ejecutan las tareas de procesamiento de datos. 

--------------------------------------------------------------------------
***APACHE BEAM***                                                                                                          18-09-2024

Es un framework de procesamiento de datos de open source  desarrollado por Google.
Su objetivo principal es proporcionar un modelo de programación unificado para el procesamiento de datos en streaming y batch (por lotes) de forma escalable.

Este modelo de programación unificado permite a los desarrolladores escribir código que funcione en diferentes motores de procesamiento de datos sin tener que preocuparse por diferencia de lógica o sintaxis.

Código portable.

Beam permite permite patrocinar los datos en ventanas de tiempo lo que es util para procesar datos en tiempo real.

Se utiliza en Windows y Linux y es gratuito.

SDK es como una tienda de herramientas que nos presta estas herramientas.
Es una librería, 


--------------------------------------------------------------------------
***APACHE KAFKA***                                           
                                                                    
                                                               23-09-2024

Es una plataforma que permite procesar y almacenar grandes cantidades de datos en una plataforma de streaming.

- Esta programada en Java y Scala.
- Es de código abierto.
- Se distribuye en licencia Apache 2.0.
- Surgió en Linkedln en 2011 como sistema de mensajería.

Arquitectura:
Actúa como un sistema de mensajería entre el emisor y receptor. Consiste una red de ordenadores en clúster(varias computadoras conectadas entre si).

Sus partes fundamentales son:
- Productores
- Consumidores
- Topicos (se ordenan por como van llegando)
- Brokers (servidores donde se almacenan los mensajes)
- Particiones (se ordena por categoría)

Caracteristicas principales:
- Alto rendimiento
- Escalable
 - Almacenamiento permanente
- Alta disponibilidad
- Costo potencialmente alto
- Consume mas energía.
- Overhead de red (cuando se tienen muchos mensajes se genera un cuello de botella)

Desventajas:
Costo potencialmente alto
consumo de recursos
curva de aprendizaje pronunciada
cuello de botella

Interfaces de kafka:
- API de productor ( se encarga de enviar los mensajes)
- API de consumidor ( lo que permite tener tolerancia a fallos por medio de estados.)
- API de flujo(proporciona una interfaz)
- API de conexión (funciona como un traductor para varios sistemas)

Solo esta disponible para Windows y Linux.

Un **clúster** en Apache Spark y Apache Kafka se refiere a un conjunto de servidores que trabajan juntos para procesar y gestionar grandes volúmenes de datos de manera eficiente.
- Clúster de Kafka: Un clúster de Apache Kafka consiste en varios brokers (servidores) que almacenan y gestionan los datos en forma de temas y particiones. 


--------------------------------------------------------------------------
***APACHE HADOOP ***


                                                                24-09-2024

Es un marco de software de código abierto utilizado para almacenar 

Requiere SSD(tiene un limite de escrituras) y HDD(son mejoras porque permite)

Software:
- Linux
- Java
- SSH


Características:
- Almacenamiento distribuido
- Escalabilidad 
- Tolerancia a fallos
- Flexibilidad

Se utiliza en Google, Facebook, Yahoo! y Amazon

Su uso ha disminuido en los últimos años debido al surgimiento de nuevas tecnologías de BigData  y procesamiento en la nube como Apache Spark, Kubernetes y servicios en la nube como AWS, Azure y Google Cloud.


Su estructura se basa en la capacidad de distribuir tareas.

HDFS es un sistema de archivos


Kubernetes,  es un gestor de microservicios.



--------------------------------------------------------------------------
***APACHE SOFTWARE FOUNDATION***

Es una organización sin fines de lucro que mantener proyectos de código abierto

Su misión es proporcionar un entorno colaborativo 

Sus proyectos son 
Apache http 

 esta enfocado en su comunidad en donde voluntarios y empresas ayudan y apoyan a los desarrolladores


Gana dinero atraves de patrosinadores por ejemplo google, microsoft y ibm 

Organiza conferencias y eventos importantes.

Su estructura se divide en 4 miembros, committers, proyectos de alto nivel, apache incubator 




---------------------------------------------------------------------

***OPEN MPI***                

                                                                24-09-2024

Es un sistema de para mensajería de la interfaz de usuario para la comunicación entre el sistema y mejorar procesamiento.

Open MPI ayuda a que computadoras trabajen juntas para resolver problemas difíciles.
Mensaje Passing Interface.
Es un entorno de programación diseñado 

Facilita la computación paralela,.Permite a los desarrolladores crear aplicaciones que puedan ejecutarse en múltiples nodos de un clúster, optimizando recursos y mejorando la eficiencia del procesamiento de datos.

Tres proyectos destacados de MPI se unieron para crear Open MPI.

Los fundamentos de Open MPI incluye la comunicación entre procesos, la gestión de recursos y el manejo de errores.



Computación paralela:
Desde simulaciones científicas hasta el procesamiento de grandes volúmenes de datos.

Se puede utilizar en linux, 

Es una libreria.
Multiplicad de procesos.





------------------------------------------------------------------------------------------------------------------------

