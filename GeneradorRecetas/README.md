# Organizador de Recetas

![Java](https://img.shields.io/badge/Java-17-blue)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)

## Descripción

**Organizador de Recetas** es una aplicación de consola desarrollada en Java que permite gestionar y organizar recetas de cocina. Los usuarios pueden agregar, visualizar, modificar, eliminar y buscar recetas según ingredientes o tiempo de preparación. Las recetas se almacenan en un archivo serializado (`recetas.ser`) dentro de un directorio `Recetas`, garantizando la persistencia de los datos entre sesiones. La aplicación incluye 50 recetas precargadas, que abarcan desde desayunos como Tostada de Aguacate hasta cenas como Lasaña y postres como Tiramisú.

El proyecto está estructurado en tres clases principales:
- **`Recetas`**: Representa una receta con atributos como nombre, lista de ingredientes, pasos de preparación y tiempo en minutos.
- **`OrganizadorRecetas`**: Contiene la lógica principal de la aplicación, ofreciendo una interfaz de menú interactiva para la gestión de recetas.
- **`GeneradorRecetas`**: Clase auxiliar que precarga 50 recetas de ejemplo en el sistema.

## Características

- **Agregar Recetas**: Permite crear nuevas recetas ingresando nombre, ingredientes, pasos y tiempo de preparación.
- **Visualizar Recetas**: Muestra una lista de todas las recetas almacenadas y permite ver detalles (ingredientes, pasos y tiempo) de una receta seleccionada.
- **Modificar Recetas**: Actualiza los datos de una receta existente reemplazándolos con nuevos valores.
- **Eliminar Recetas**: Permite eliminar recetas no deseadas de la colección.
- **Búsqueda por Ingredientes**: Encuentra recetas que contengan un ingrediente específico.
- **Búsqueda por Tiempo**: Lista recetas que requieran al menos un tiempo de preparación especificado.
- **Búsqueda Combinada**: Busca recetas según ingrediente y tiempo mínimo de preparación.
- **Almacenamiento Persistente**: Las recetas se guardan en un archivo (`recetas.ser`) y se cargan automáticamente al iniciar la aplicación.
- **Recetas Precargadas**: Incluye 50 recetas de ejemplo, como Espaguetis a la Carbonara, Tacos de Carne, Sopa de Lentejas y más.

## Requisitos

- **Java**: Versión 17 o superior.
- Un entorno de desarrollo (como NetBeans, IntelliJ IDEA o Eclipse) o un compilador de Java para ejecutar la aplicación desde la terminal.

## Instalación

1. **Clonar el Repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/organizador-recetas.git
   cd organizador-recetasta el archivo LICENSE para más detalles.
