![technology Gradle](https://img.shields.io/badge/technology-Gradle-blue.svg)
![homebrew](https://img.shields.io/homebrew/v/cake)
![Open Collective sponsors](https://img.shields.io/opencollective/sponsors/shields)
![GitHub commits since tagged version (branch)](https://img.shields.io/github/commits-since/whuera/install-brew/1.0/master)


# install-brew steps for Linux distro debian / ubuntu 20.04

    
install brew tool in linux

## follow next steps:
1. sudo apt-get install curl
2. sudo apt-get install build-essential curl file git
3. sh -c "$(curl -fsSL https://raw.githubusercontent.com/Linuxbrew/install/master/install.sh)"
4. echo 'export PATH="/home/linuxbrew/.linuxbrew/bin:/home/linuxbrew/.linuxbrew/sbin/:$PATH"' >>~/.bashrc
5. echo 'export MANPATH="/home/linuxbrew/.linuxbrew/share/man:$MANPATH"' >>~/.bashrc
6. echo 'export INFOPATH="/home/linuxbrew/.linuxbrew/share/info:$INFOPATH"' >>~/.bashrc
7. source  ~/.bashrc

#### Finally steps and test

8. brew install gcc
9. brew update
10. brew list
   
![fork my repository](https://github.com/user/repository/fork)
![watch this repo](https://github.com/user/repository/subscription)  
   
   # Template Feactures for repo

El propósito de esta aplicación es resolver las notificaciones que se envían por alcanzar algún hito por el programa de Mercado Puntos. 

![arquitectura](https://github.com/mercadolibre/fury_loyal-notifications/blob/master/app.png)


# Java Gradle Starter App

![technology Gradle](https://img.shields.io/badge/technology-Gradle-blue.svg)

This is a basic Java Gradle application created by Fury to be used as a starting point for your project.

## Usage

1. In your Dockerfile, specify the correct tag for your app.

   **E.g.:**

   `FROM hub.furycloud.io/mercadolibre/java-gradle:jdk8`

   #### Available tags

   You can find all available tags for your Dockerfile [here](https://github.com/mercadolibre/fury-docker_images/blob/master/java-gradle/README.md#available-tags)

2. Set the CodeCov token environment variable as shown [here](https://github.com/mercadolibre/fury-docker_images/blob/master/java-gradle/README.md#codecov)

3. If you need to, modify the default Gradle tasks that you see fit as shown [here](https://github.com/mercadolibre/fury-docker_images/blob/master/java-gradle/README.md##environment-variables)

4. Start coding!


#### Postman Collection - Send email
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/7365e9c559dec6402275)

## Questions

* [ci-cd@mercadolibre.com](ci-cd@mercadolibre.com)
* [fury@mercadolibre.com](fury@mercadolibre.com)


### Partners features

[**Agregar mensaje Toast para dispositivos IOS**]

**Breve descripción de los cambios** 

Se agrega el componente toast que se ancla al final de la pantalla (para dispositivos ios), que muestra el mensaje al usuario para el CU-MP_PACK_CONSUMED. 

Integración Front + Back lista: SI 

 
**Descripción de las pruebas**



Scope Front: testbeta
Scope Middleend: test3

| Platform |  Partner  |      Escenario     |      Respuesta      |  Comentarios  |
| --------- | -------- | ---------------- | ----------------- | -------------- |
|        mobile      |    Disney    | | ![image](https://user-images.githubusercontent.com/72230338/95878514-e8cdd580-0d3a-11eb-8300-c20a0d13d1ce.png)   |  el botón aparece en la parte de atrás porque no se puede probar en native  |



