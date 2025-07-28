## 2. Proyecto Paso a Paso  ##
### Cuestionario ###
1. ¿Qué tipo de terminal es una EL1904, EL6910 y EL2904?
2. ¿Los terminales seguros tienen direccionamiento?
3. ¿Se puede configurar la dirección 0?
4. ¿Qué tipo de proyecto de seguridad debo añadir si voy a descargarlo en una EL6910?
5. ¿Qué son los Alias Devices en un proyecto de seguridad?
6. ¿Qué es el fichero .sal de un proyecto de seguridad?
7. ¿Dónde puedo seleccionar el hardware al que voy a descargar el proyecto de seguridad?
8. ¿Qué dos tipos de alias existen en un proyecto de seguridad?
9. ¿Qué tipo de alias debo utilizar para vincular un BOOL entre el proyecto de PLC y el proyecto de seguridad?
10. ¿Que permite la opción de *Import Alias Devices from IO*?
11. ¿En que esclavo EtherCAT se quedan relejados todos los alias en su *process data*?
12. ¿Dónde puedo configurar la dirección FSoE de un Alias?
13. ¿Que checkbox debo activar en el alias de la EL1904 para poder leer el estado de sus 4 entradas desde PLC?
14. ¿Que checkbox debo activar en el alias de la EL1904 para poder leer el estado y diagnóstico de la comunicación desde PLC?
15. ¿En que pestaña del alias de la EL1904 puedo configurar el modo de operación de las entradas?
16. ¿Dónde comprobar que la detección de consumo mínimo de las salidas de la EL2904 está activa?
17. ¿Dónde puedo cambiar en el alias de la EL2904 los nombres de las salidas?
18. ¿Que FB de seguridad debo usar para hacer un *emergency stop*?
19. ¿Como se puede configurar la entrada 1 del *emergency stop* para que trabaje con control de discrepancia?
20. ¿Cuál es la pestaña que permite crear y vincular variables en el proyecto de seguridad?
21. ¿Puedo vincular a más de un alias una variable de salida del proyecto de seguridad?
22. ¿Es estrictamente necesario vincular la señal de Run y ErrorAck del grupo de seguridad cuando corre en una EL6910?
23. ¿En que pestaña puedo activar las variables de diagnóstico de grupo (*State* y *Diag*)?
24. ¿Como norma general, después de descargar un proyecto de seguridad, debo hacer un *activate configuration* y *login*?
25. ¿Cual es el usuario y password por defecto para descargar un proyecto de seguridad a una EL6910?

### Práctico ###
1. Crea un proyecto de seguridad asociado al demo kit de safety de formació. El contactor se debe activar al pulsar el botón de rearme siempre que la seta de emergencia no esté enclavada. Crea un proyecto de PLC para enviar el *Run* y *ErrrAck* al PLC de seguridad. 