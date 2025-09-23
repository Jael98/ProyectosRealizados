Organizador de Recetas
Descripción
Organizador de Recetas es una aplicación en Java diseñada para gestionar recetas de cocina de manera sencilla y eficiente. Permite a los usuarios crear, consultar, modificar y eliminar recetas, así como realizar búsquedas basadas en ingredientes o tiempo de preparación. Las recetas se almacenan en un archivo serializado (recetas.ser) dentro de una carpeta llamada Recetas.
Características

Añadir recetas: Ingresa el nombre, ingredientes, pasos y tiempo de preparación de una receta.
Mostrar recetas: Visualiza una lista de recetas almacenadas y consulta los detalles de una receta específica.
Modificar recetas: Actualiza la información de una receta existente.
Eliminar recetas: Borra recetas de la lista.
Búsqueda por ingredientes: Encuentra recetas que contengan un ingrediente específico.
Búsqueda por tiempo: Lista recetas que requieren un tiempo de preparación igual o superior al especificado.
Búsqueda combinada: Busca recetas que cumplan con criterios de ingredientes y tiempo simultáneamente.
Persistencia de datos: Las recetas se guardan en un archivo serializado para mantener los datos entre sesiones.

Estructura del Proyecto
El proyecto está organizado en el paquete com.mycompany.creadorrecetas y contiene las siguientes clases:

OrganizadorRecetas.java: Clase principal que contiene la lógica del programa, incluyendo el menú interactivo y las operaciones de gestión de recetas.
Recetas.java: Clase que define el objeto Recetas, con atributos como nombre, lista de ingredientes, lista de pasos y tiempo de preparación. Implementa la interfaz Serializable para permitir la persistencia de datos.
GeneradorRecetas.java: Clase auxiliar que genera un conjunto inicial de 50 recetas predefinidas y las guarda en el archivo recetas.ser.

Instalación

Clona el repositorio en tu máquina local:git clone <https://github.com/Jael98/ProyectosRealizados.git>


Asegúrate de tener instalado Java (JDK 8 o superior).
Abre el proyecto en un IDE compatible con Java (como NetBeans, IntelliJ o Eclipse).
Compila y ejecuta la clase OrganizadorRecetas.java para iniciar el programa, o GeneradorRecetas.java para crear un conjunto inicial de recetas.

Uso

Al iniciar el programa, se crea automáticamente una carpeta llamada Recetas si no existe.
El programa carga cualquier receta previamente guardada en Recetas/recetas.ser.
Se presenta un menú interactivo con las siguientes opciones:
1. Añadir Receta: Ingresa una nueva receta.
2. Mostrar lista de recetas: Muestra todas las recetas y permite ver los detalles de una.
3. Modificar receta: Actualiza una receta existente.
4. Eliminar receta: Borra una receta de la lista.
5. Búsqueda de alimentos: Busca recetas por ingrediente.
6. Búsqueda por tiempo: Busca recetas por tiempo de preparación.
7. Búsqueda alimentos y tiempo: Combina ambos criterios de búsqueda.
8. Salir: Cierra el programa.


Sigue las instrucciones en pantalla para interactuar con el menú.

Ejemplo de Recetas
El archivo GeneradorRecetas.java incluye 50 recetas predefinidas, como:

Espaguetis a la Carbonara (20 minutos)
Tostada de Aguacate (10 minutos)
Sopa de Verduras (30 minutos)
Galletas de Chispas de Chocolate (25 minutos)
Tiramisu (20 minutos)

Ejecuta GeneradorRecetas.java para cargar estas recetas en el archivo recetas.ser.
Requisitos

Java Development Kit (JDK) 8 o superior.
Un IDE o entorno que soporte Java.
Espacio en disco para la carpeta Recetas y el archivo recetas.ser.

Notas

El programa maneja excepciones para entradas inválidas (como números no enteros) y errores de archivo.
Las recetas se almacenan en un archivo serializado (recetas.ser), lo que asegura la persistencia entre sesiones.
Actualmente, no se ha implementado la funcionalidad para clasificar recetas por tipo de comida (desayuno, comida, cena), pero está contemplada en los comentarios del código como una mejora futura.

Contribuciones
¡Las contribuciones son bienvenidas! Si deseas colaborar, por favor:

Haz un fork del repositorio.
Crea una rama para tu funcionalidad (git checkout -b feature/nueva-funcionalidad).
Realiza tus cambios y haz commit (git commit -m 'Añadir nueva funcionalidad').
Sube los cambios a tu repositorio (git push origin feature/nueva-funcionalidad).
Crea un Pull Request para revisión.

Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
