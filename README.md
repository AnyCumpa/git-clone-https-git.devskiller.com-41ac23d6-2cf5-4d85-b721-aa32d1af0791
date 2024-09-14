# Automatización de Servicio - RestAssured

### Este es un proyecto basado en:

- Maven
- Java
- SerenityBDD
- JUnit5
- RestAssured

### ¡IMPORTANTE! Lee atentamente las indicaciones del ejercicio.

Página que contiene las especificaciones de las APIS (contrato)<br>
Ingresa a la siguiente ruta y consulta los servicios disponibles.<br>

#### -> https://reqres.in/

**ReqRes.in** es un sitio que expone un Servicio Web sencillo, que usaremos para resolver el siguiente desafio:

### Descripción del ejercicio

### ===> Recomendaciones Importantes

1. El proyecto ya tiene código desarrollado reutilizable, por lo tanto, **reutilicemos métodos y variables** existentes.
2. Debes completar los siguientes **'@Test'** que se encuentran en la clase **'UserApiTest.java'** para que funcionen:

```java
//Validar que la URL base sea la correcta
@Test
public void validarURLBase(){}

//Validar que el código de respuesta sea el correcto
//indicado en la especificación del servicio
@Test
public void validarCodigoDeRespuesta(){}

//Validar que el número de páginación indicado en el desafio
//se encuentre en la respuesta del servicio indicado
@Test
public void validarNumeroPaginaEnRespuesta(){}
```

3. El proyecto tiene ciertos incidentes que nos llevarán al error. **Corrijamos estos incidentes para continuar.**
4. **_Ayuda:_** la mayoria de incidentes están en la clase **'BaseTest.java'**


### ===> Desafio

1. Identifiquemos el servicio **'LIST USERS'** con el endpoint **'/users'** y el método **'GET'** en la página **-> https://reqres.in/**
2. Se solicita obtener toda la lista de usuarios por página, en este caso, la página número **'2'**
3. Una vez que obtengamos la lista de usuarios, validar lo siguiente:
    4. **Que, el estado de la respuesta sea la correcta (OK)**
    5. **Que, dentro de la respuesta del servicio se encuentre el número de paginación solicitado en el punto (2)**


### Por último ...

#### 1. Lee bien los comentarios que existen en el proyecto, esto te ayudará a ubicarte y te permitirá empezar a resolver el ejercicios.
#### 2. Ejecuta y valida los test en su totalidad con ayuda del comando:

```
$ mvn clean test
```

#### 3. Una vez que hayas terminado con los desafios, no te olvides de publicar tus cambios con Git, de lo contrario, no podrán ser evaluados:<br>
Utiliza la siguiente secuencia de comandos
```
$ git add .
$ git commit -m "solution"
$ git push
```


