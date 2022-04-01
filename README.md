# Servicio-Web-REST
Implementación de un servicio web estilo REST utilizando la API de java JAX-RS sobre el servidor de aplicaciones Tomcat

## __Instalación__

### __Instalar JDK8__
Como primer paso instalaremos JDK8 y JRE8, para facilitar la instalación usaremos el script [**java8.sh**][DOWNLOADJAVA8]

```bash
#!/bin/bash

#Primero daremos permiso al script para poder ejecutar con el siguiente comando
# chmod +x script.sh

sudo apt-get update
sudo apt.get upgrade

#Instalamos el jre y jdk

sudo apt install openjdk-8-jre-headless
sudo apt install openjdk-8-jdk-headless

exit
```

### __Instalar Tomcat8__
Descargar la distribución binaria de Tomcat8 de la pagina oficial de descarga: [https://tomcat.apache.org/download-80.cgi][DOWNLOADTOMCAT8] (Descargar la opción core "zip") [Descarga directa][DOWNLOADTOMCAT8DIRECT]



<!-- Enlaces requeridos por el Readme -->
[DOWNLOADJAVA8]: https://github.com/Caiuss24001000/Servicio-Web-REST/blob/main/java8.sh "script java8.sh"
[DOWNLOADTOMCAT8DIRECT]: https://dlcdn.apache.org/tomcat/tomcat-8/v8.5.77/bin/apache-tomcat-8.5.77.zip "Download Tomcat8.zip"
[DOWNLOADTOMCAT8]: https://tomcat.apache.org/download-80.cgi "Tomcat8"
