# LeerArchivoPersona
Actividad Obligatoria para el portafolio 2019 (ambos turnos)
Colecciones - Archivos - Entrada/Salida - Excepciones.

Implementar un método estático getPersonas que reciba el nombre de un archivo “personas.in” y devuelva un objeto LinkedList<Persona> con personas que fueron leídas del archivo de texto con formato: dni apellido edad (tres campos separados por un espacio en blanco). 
Implementar un método estático getPersonasOrdenadasPorDni que reciba un objeto LinkedList<Persona> y devuelva otro objeto LinkedList<Persona> con las personas ordenadas por DNI (no se debe modificar el objeto LinkedList<Persona> que se recibe por parámetro). 
Implementar un método estático getPersonasMayoresAEdad que reciba un objeto LinkedList<Persona> y una edad y devuelva otro objeto LinkedList<Persona> con las personas cuyas edades son mayores a esa edad (no se debe modificar el objeto LinkedList<Persona> que se recibe por parámetro). 
Implementar un método estático listarPersonas que reciba por parámetro un objeto LinkedList<Persona> y un String (que será el nombre del archivo de salida).  Usar este método para generar los archivos “personaOrdenadasPorDni.out” y “personasMayores.out” a partir los LinkedList<Persona> obtenidos en los  puntos 2 y 3. Tenga en cuenta que para ésto, deberá sobreescribir el método toString de Object para aplanar el objeto Persona a una cadena que contiene los colaboradores internos del objeto separado por “;”.

Resolver el problema “Descubriendo nombres repetidos" aplicando Maps. La solución implementada debe ser capaz de procesar el archivo “400000nombres.in”
