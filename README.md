# Spring Boot Application

Este es un proyecto de introduccion a spring boot, se hacen las configuraciones basicas que permiten generar conocimiento sobre como se utiliza esta tecnolgia.

### Requisitos

- Java 17 o superior
- Maven 3.6 o superior

### Configuración

Los pasos iniciales para elaborar este proyecto son los siguientes:

1. Se creo un archivo `pom.xml` con las dependencias necesarias para un proyecto Spring Boot, que luego se muestra el arbol de las dependecias usando el comando `mvn dependency:tree`.
2. Se creo la clase principal `MyApplication.java` que contiene el método `main` creando manualmente las siguientes carpetas:
    - `src/main/java/com/example/`
3. Dentro de la carpeta `com/example/`, se creo la clase `MyApplication.java` el cual se ha importado algunos paquetes de spring boot.
  
```java
import org.springframework.boot.SpringApplication; 
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

//code...
```
4. 

### Ejecución

Para ejecutar la aplicación, navega al directorio del proyecto y utiliza el siguiente comando:

```
mvn spring-boot:run
```

