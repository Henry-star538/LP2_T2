# Blockbuster Fake - Alquiler de Películas

Sistema para la gestión de alquileres y devoluciones de películas, desarrollado con **Spring Boot**, **Thymeleaf** y **MySQL**.

## Descripción

Este proyecto permite registrar clientes, películas, alquileres y devoluciones. Incluye una interfaz moderna basada en Thymeleaf.

## Características

- Registro, edición y eliminación de clientes.  
- Registro y gestión de películas.  
- Registro de alquileres.  
- Registro de devoluciones.  
- Interfaz web amigable y moderna.  

## Tecnologías utilizadas

- Java 17  
- Spring Boot 3.5.x  
- Spring Data JPA  
- Thymeleaf  
- MySQL  
- Maven  
- Lombok  

## Configuración del proyecto

1. Clona el repositorio:

   ```bash
   git clone [https://github.com/Henry-star538/LP2_T2]
   
2. Configura la base de datos MySQL:

   - Crea una base de datos con el nombre que desees.

   - Actualiza el archivo src/main/resources/application.properties con tus credenciales de tu base de datos mysql.
          spring.datasource.username=tu_usuario
          spring.datasource.password=tu_contraseña

3. Construye y ejecuta la aplicación: mvn spring-boot:run

4. Accede a la aplicación: Abre tu navegador en http://localhost:8085/inicio
   

AUTOR: Henry Culqui
