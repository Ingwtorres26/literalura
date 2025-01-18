# Literalura - Catálogo de Libros por Consola

Literalura es una aplicación desarrollada en Java utilizando Spring Boot y PostgreSQL. Permite gestionar un catálogo de libros y consultar información sobre libros, autores y categorías mediante una interfaz de consola.

## Características principales

1. **Buscar libros por título:**
   - Permite al usuario buscar libros en la API de Gutendex.
   - Si el libro se encuentra, se registra en la base de datos y se muestra información relevante:
     - Título
     - Autor
     - Idioma
     - Número de descargas

2. **Listar los libros registrados:**
   - Muestra todos los libros almacenados en la base de datos junto con su información.

3. **Listar autores registrados:**
   - Presenta una lista de autores registrados con los siguientes detalles:
     - Nombre
     - Fecha de nacimiento
     - Fecha de fallecimiento (si aplica)
     - Libros asociados registrados en el sistema.

4. **Listar libros por idioma:**
   - Permite al usuario elegir un idioma registrado en la base de datos y muestra los libros disponibles en ese idioma.

5. **Opción de salir:**
   - Finaliza la ejecución de la aplicación.

## Tecnologías utilizadas

- **Java**: Lenguaje de programación principal.
- **Spring Boot**: Framework para desarrollo rápido de aplicaciones.
- **PostgreSQL**: Base de datos utilizada para almacenar los datos del catálogo.
- **Gutendex API**: Fuente de información para buscar libros en línea.
- **IntelliJ IDEA**: IDE utilizado para el desarrollo.

## Requisitos previos

- Java 17 o superior
- PostgreSQL configurado y corriendo
- IDE como IntelliJ IDEA
- Maven configurado para gestionar dependencias

## Instalación y configuración

1. Configura la base de datos PostgreSQL:
   - Crea una base de datos llamada `literalura`.
   - Actualiza las credenciales en el archivo `application.properties`.

2. Instala las dependencias del proyecto:
   ```bash
   mvn clean install
   ```

3. Ejecuta la aplicación:
   ```bash
   mvn spring-boot:run
   ```

## Uso

1. Al iniciar la aplicación, se mostrará un menú con las opciones disponibles.
2. Selecciona una opción ingresando el número correspondiente.
3. Sigue las instrucciones en pantalla para realizar las consultas o acciones deseadas.
4. Utiliza la opción `Salir` para finalizar la ejecución.

## Contribuciones

Contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request si tienes sugerencias o mejoras.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

