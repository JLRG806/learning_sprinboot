# Spring Boot Application

Este es un proyecto de introduccion a spring boot, se hacen las configuraciones basicas que permiten generar conocimiento sobre como se utiliza esta tecnolgia.

### Requisitos

- Java 17 o superior
- Maven 3.6 o superior

### Configuración

Los pasos iniciales para elaborar este proyecto son los siguientes:

1. Se creo un archivo `pom.xml` con las dependencias necesarias para un proyecto Spring Boot, que luego se muestra el arbol de las dependecias, usando el comando `mvn dependency:tree`.
2. Se creo la clase principal `MyApplication.java` que contiene el método `main` ubicado en las carpetas creadas manualmente:
    - `src/main/java/com/example/MyApplication.java`
3. En la clase `MyApplication.java` se han importado algunos paquetes de spring boot.
  
```java
import org.springframework.boot.SpringApplication; 
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

//code...
```
4. He aprendido sobre las anotaciones  `@RestController` y `@SpringBootApplication` que son fundamentales para crear aplicaciones web con Spring Boot.
    - `@RestController`: Indica que la clase es un controlador REST, lo que significa que puede manejar solicitudes HTTP y devolver respuestas en formato JSON o XML.
    - `@SpringBootApplication`: Marca la clase principal de la aplicación Spring Boot y habilita la configuración automática y el escaneo de componentes.
5. Se ha definido un endpoint básico en la aplicación utilizando la anotación `@RequestMapping("/")`, que responde con un mensaje JSON cuando se accede a la raíz del servidor.
6. Se como crear archivos jar ejecutables usando Maven con el comando `mvn package`.

### Ejecución

Para ejecutar la aplicación, navega al directorio del proyecto y utiliza el siguiente comando:

```
mvn spring-boot:run
```

Se abrira un servidor web en `http://localhost:8080`, y al acceder a esta URL, deberías ver el mensaje JSON `{"message": "Hello World!"}`.


### Dudas y concluciones

Me interesa saber que es lo que sigue en el tutorial de Spring?

Que arquitecturas se pueden aplicar con srping boot?

Como se maneja las peticiones con parametros en body, query, y req-form?

Como se maneja JSON dentro de la aplicacion?

De que manera puedo especificar los puertos en los que quiero que el servidor se exponga?

Hasta ahora he navegado un poco sobre este entorno de trabajo, me ha parecido algo muy sencillo de utilizar, practicare mas

