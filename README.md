# Charlas Técnicas

## VisualStudio.com

VisualStudio.com - Administración del proyecto.<br>
[![VisualStudio.com - Administración del proyecto](https://img.youtube.com/vi/CYcJIDzInQ4/0.jpg)](https://www.youtube.com/watch?v=CYcJIDzInQ4)

**Agregar un administrador al proyecto**<br>
![Agregar administrador al proyecto](https://raw.githubusercontent.com/alejocram/pi1-charlas_tecnicas/master/Add_Admin_to_VS.jpg "Agregar administrador al proyecto")
1. Ingresa al proyecto en VisualStudio.com.
2. Selecciona Configurar y luego Seguridad.
3. Selecciona el grupo Project Administrators.
4. Selecciona Members.
5. Y agrega uno nuevo, colocando el correro del integrante del proyecto que deseas que también sea administrador del proyecto.

## HTML, CSS & JS
En el siguiente link [_MDN html tutotial_](https://developer.mozilla.org/en-US/docs/Learn/HTML) encontras una guia muy completa para aprender sobre HTML, CSS y javascript. 
Una guia un poco mas completa sobre javascript, css y sus diferentes tecnologias web se puede encontrar en [_The Odin Project Javascript_](https://www.theodinproject.com/courses/javascript) y [The Odin Project CSS](https://www.theodinproject.com/courses/html5-and-css3). 

## NodeJS 

- Instalar NPM
- Instalar NodeJS
- Instalar WebStorm (con correo de EAFIT) o ATOM
- Instalar Postman
- Descargar el [proyecto](https://github.com/alejocram/pi1-charlas_tecnicas/raw/master/41-ExpressExample.zip) y descomprimirlo

Desde consola
Ubicarse dentro del proyecto Ej: /Desarrollo/NodejsProjects/Examples/ExpressExample
`npm start` 
 
Desde el browser
http://localhost:3000
 
http://localhost:3000/users

Desde Postman
POST http://localhost:3000

```
{ "text":"Proyecto Integrador", "title":"Curso" }
```

Recibes un response
```
{ "success": true, "response": { "text": "Proyecto Integrador", "title": "Curso" } }
```

Vuelve a verificar el browser, veras el cambio 

_**Express tutorial**_
En el siguiente link [_MDN express tutorial_](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs) encontras un tutorial muy completo creado por la comunidad de MDN para aprender a usar el framework [_express js_](https://expressjs.com/).

## Django (python)
En el siguiente link [MDN Django tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django) encontrars un tutorial muy completo creado por la comunidad de MDN para aprender a usar el framework [Django framework](https://www.djangoproject.com/).

## Android 

- Instalar Java SDK
- Instalar Android Studio
- Descargar el [proyecto](https://github.com/alejocram/pi1-charlas_tecnicas/raw/master/42-ParkingMovil.zip) y descomprimirlo

El proyecto de ejemplo implementa la libreria Volley para el consumo de WebServices y el patrón MVC, además también se implementa el patrón Singleton.

El proyecto consume un servicio REST que retorna un JSON con bloques de la Universidad, luego se almacena en un arrayList y finalmente se pasa el array a un String.

En el siguiente link pueden encontrar un tutorial de Google para el desarrollo de Material Design en la aplicación.
https://codelabs.developers.google.com/codelabs/material-design-style-sp/index.html#0

**Android tutoriales**<br>
[Android Development Tutorials](https://www.raywenderlich.com/category/android)

## IONIC 2

Charla de Julian Andres Gamez de IdeasLab
[![Charla de Julian Andres Gamez de IdeasLab](https://img.youtube.com/vi/Kbz_e-qgmCY/0.jpg)](https://www.youtube.com/watch?v=Kbz_e-qgmCY)

Instalación de IONIC 2
[![Instalación de IONIC 2](https://img.youtube.com/vi/kBWmDmzjk8E/0.jpg)](https://www.youtube.com/watch?v=kBWmDmzjk8E)

Primera Aplicación en IONIC 2
[![Primera Aplicación en IONIC 2](https://img.youtube.com/vi/buSz-V39f1A/0.jpg)](https://www.youtube.com/watch?v=buSz-V39f1A)

Editar Aplicaciones de IONIC con Visual Studio Code
[![Editar Aplicaciones de IONIC con Visual Studio Code](https://img.youtube.com/vi/J3zh5b9q1x4/0.jpg)](https://www.youtube.com/watch?v=J3zh5b9q1x4)

Ionic Crash Course (2.x and above)
[![Ionic Crash Course (2.x and above)](https://img.youtube.com/vi/O2WiI9QrS5s/0.jpg)](https://www.youtube.com/watch?v=O2WiI9QrS5s)

[Get started with Ionic Framework](https://ionicframework.com/getting-started)

## Spring 

**Instalación**<br> 
-Instalar [Java JDK](http://www.oracle.com/technetwork/java/javase/downloads)

-Definir la variable de entorno JAVA_HOME
 Debes obtener la ruta de instalación del JDK.
 ```sh
 C:\Program Files\Java\jdk1.8.0_161
 ```

 Once you have the JDK installation path:

  1. Right-click the My Computer icon on your desktop and select Properties.
  2. Click the Advanced tab, then click the Environment Variables button.
  3. Under System Variables, click New.
  4. Enter the variable name as JAVA_HOME.
  5. Enter the variable value as the installation path for the Java Development Kit.
  6. Click OK.
  7. Click Apply Changes.
 Note: You might need to restart Windows.

Descarga Spring Tool Studio y descomprime.
https://spring.io/tools/sts/all
Y dentro de la carpeta encontrarás el ejecutable
..\sts-bundle\sts-3.9.2.RELEASE
Puedes crear un acceso directo en el Escritorio. 

**Soporte a proyectos con Gradle**<br>
Dirígete al Eclipse Marketplace, busca por Buildship Gradle. <br>
Instala el Buildship Gradle Integration. <br>
Help > Eclipse Marketplace. <br>
![Buildship gradle](https://raw.githubusercontent.com/alejocram/pi1-charlas_tecnicas/master/Items.png "Gradle")

**Spring Boot Tutorial - Hello World**<br>
En este primer video, se presentan los pasos para realizar una aplicación básica con Spring Boot.
[![Spring Boot Tutorial - Hello World](https://img.youtube.com/vi/mN_9sKco_DQ/0.jpg)](https://youtu.be/mN_9sKco_DQ)

**Build JAR with Gradle**<br>
Para realizar el despliegue sobre un servidor, se requiere empaquetar en el JAR todas las librerias.
En el archivo `build.gradle` debes agregar las siguientes lineas.
```sh
bootJar {
    baseName = 'gs-rest-service'
    version =  '0.1.0'
}
```
Y luego debes de compilar


**Spring Boot Tutorial - Build JAR with Maven**<br>
Para realizar el despliegue sobre un servidor, se requiere empaquetar en el JAR todas las librerias.
En el archivo `pom.xml` debes agregar las siguientes lineas.
```sh
<build>
	<plugins>
		<plugin>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-maven-plugin</artifactId>
		</plugin>
	</plugins>
</build>
```
Y luego debes de compilar bajo el comando de maven `mvn package`.
O lo puedes realizar desde el Spring Tools Suite, como se presenta en el siguiente video.
[![Spring Boot Tutorial - Build JAR with Maven](https://img.youtube.com/vi/qDTUYkaXAEc/0.jpg)](https://youtu.be/qDTUYkaXAEc)

**Crea un Azure Web App para usar con Java**<br>
En el siguiente link encontraras los pasos para realizar la configuración del Azure Web App Java.
También se indica las credenciales para subir los archivos `web.config` y `jar` por medio de una [cliente FTP](https://filezilla-project.org/download.php?type=client).
[![Create an Azure web app for use with Java](https://github.com/Azure/azure-docs-sdk-java/raw/master/docs-ref-conceptual/spring-framework/media/deploy-spring-boot-java-web-app-on-azure/AZ01.png)](https://github.com/Azure/azure-docs-sdk-java/blob/master/docs-ref-conceptual/spring-framework/deploy-spring-boot-java-web-app-on-azure.md#create-an-azure-web-app-for-use-with-java).
[Create an Azure web app for use with Java](https://github.com/Azure/azure-docs-sdk-java/blob/master/docs-ref-conceptual/spring-framework/deploy-spring-boot-java-web-app-on-azure.md#create-an-azure-web-app-for-use-with-java).

## Ruby OnRails

[![Ruby OnRails](https://img.youtube.com/vi/BAVuEhWLt3w/0.jpg)](https://youtu.be/BAVuEhWLt3w)

_**Tutorial de Ruby on Rails**_ 
[The Odin Project Rails Tutorial](https://www.theodinproject.com/courses/ruby-on-rails) 

## ASP.NET

**Instalación**<br> 
En el siguiente link encontraras los pasos para realizar la instalación del .Net Core y Visual Studio para cualquier sistema operativo, [Install Visual Studio and .NET Core](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/start-mvc?tabs=aspnetcore2x&view=aspnetcore-2.1#install-visual-studio-and-net-core "Install Visual Studio and .NET Core").<br> 
-Instalar [Visual Studio Community](https://www.visualstudio.com/es/downloads/).
-En la instalación recuerda agregar el modulo de ASP.NET y desarrollo web.

**Crear una API web con ASP.NET Core y Visual Studio**<br> 
![Diseño básico de la aplicación TODO](https://docs.microsoft.com/es-es/aspnet/core/tutorials/first-web-api/_static/architecture.png "Diseño básico de la aplicación TODO")

En el siguiente tutorial se crea la API para administrar una lista de tareas pendientes.
[Crear una API web con ASP.NET Core y Visual Studio](https://docs.microsoft.com/es-es/aspnet/core/tutorials/first-web-api).

Se recomienda descargar [Postman](https://www.getpostman.com/) para realizar las pruebas de los WebServices.
![](https://docs.microsoft.com/es-es/aspnet/core/tutorials/first-web-api/_static/pmc.png "Postman")

**Publicar en Azure**<br> 
A continuación se indica los pasos para realizar la publicación del proyecto desde Visual Studio.
Si el proyecto no tiene Base de datos, omite estos pasos en el tutorial.
[Deploy the app to Azure](https://docs.microsoft.com/en-us/aspnet/core/tutorials/publish-to-azure-webapp-using-vs?view=aspnetcore-2.1#deploy-the-app-to-azure).
![](https://docs.microsoft.com/en-us/aspnet/core/tutorials/publish-to-azure-webapp-using-vs/_static/pub.png?view=aspnetcore-2.1)


