# Redes-de-computadores

  Clase 1 
  
Elementos de una red :  nodo, enlaces y los protocolos (conjunto de reglas que indican como 2 entidades se van a comunicar)
Simplex = una direccion , half - duplex = uno doble y uno simple , full-duplex = varias direcciones

  Clase 3
  
Complejidad del software de redes.
-se necesita saber de donde viene información ( mecanismos para indetificar remitente y recibidor ), transferencia de datos (simplex, etc), control de errores y deteccion de recepcion, orden de mensajes, velocidades distintas de transmision y; recepcion y encaminamiento.

Protocolos para realizar un buen software de redes : Formateo, metodo, como y cuando e;  inicio y terminacion
Jerarquía de protocolos

Jerarquía de protocolos (Termino de "pila", se orfanizan como tal). Servicios, ofrece un inferior a un superior (pila)

Tipos de servicios
-Orientado a la conexion (son como una cola)
-Servicios sin conexión (Pueden ir como quieran, no tienen un tubo que los guien)


Estándares (Los realiza a travez de los RFC's (Requests for comments))
*Conjunto de normas y recomendaciones tecnicas que regulan la transmision en los sistemas de comunicaciones
-Estandares propietarios (entre la misma compañia)
-De jure (por una organizacion formal, organizacion se ponen de acuerdo para liberarlo, Ejemplo USB)
-De facto (aceptados naturalmente por la industria; ejemplo IBM PC)


Encapsulamiento

rodea datos con informacion de protocolo necesaria (teoria de la caja dentro de la caja en el barco)
-PDU (unidad de datos de protocolo) : contenido de datos que realmente sirve

---------------------------------------------------------------------------


Clase 4

Modelo OSI (Interconexion de sistemas Abiertos)
tiene 7 niveles (capas)
Capa Física: se encarga de la transmision de cadena de bits sobre el medio físico.
Capa de enlace de Datos: Proporciona un servicio de transferencia de datos fiable a través del enlace físico.
Capa de red : Permite la interconexion de distintas redes; Realiza la asignacion de direcciones lógicas y determina como se encaminan los paquetes desde su origen hasta su destino.
(Sali antes, ver los otros niveles).


----------------------------------------------------------------------------------

Clase 5

Modelo TCP/IP (nombre dado por sus dos protocolos primarios Transmission control protocol/ internet protocol): coleccion de protocolos que se han especificado como estandares por internet.
 
 *principios clave para tcp/ip
 ->end to end : Los mecanismos (protocolos) para proveer comunicación deben ser implementados en los nodos finales, minimizando la participación de los demás dispositivos de red.(todo el trabajo se presenta en los nodos finales, no intermedios)
 ->principio de robustez: un sistema debe ser conservador al emitir, pero liberal como receptor(en sentido de respetar o no protocolos).
 
 Capas tcp/ip 
 
 -Capa de Acceso a la Red (capa fisica y enlace de datos): Es responsable del intercambio de datos entre el nodo y la red a la cual está conectado.
 -Capa de internet (capa de red): utiliza protocolo IP,permite que los datos atraviesen las distintas redes interconectadas.
 -Capa de transporte : utiliza TCP/UDP, permite la multiplexacion de aplicaciones.Se asegura que la informacion llegue a la aplicacion correcta.
 -Capa de Aplicación(capa de sesion, presentacion y aplicación): Utiliza multiples protocolos, Contiene la logica necesaria para la comunicacion entre las distintas aplicaciones.
 

 







