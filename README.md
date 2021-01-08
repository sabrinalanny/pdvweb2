# React + Springboot JWT Authentication

## Implementação baseada no tutorial bezkoder.

## Front 

* React 16
* react-router-dom 5.1.2
* axios 0.19.2
* react-validation 3.0.7
* Bootstrap 4
* validator 12.2.0

## Back 

* Java 8
* Spring Boot 2.4.1 (with Spring Security, Spring Web, Spring Data JPA)
* jjwt 0.9.1
* MySQL
* Gradle 6

### POST	
	/api/auth/signup	criar nova conta
### POST
	/api/auth/signin	login
### GET	
    /api/test/all	conteúdo público
### GET	
	/api/test/user	conteúdo de usuário
### GET	
	/api/test/mod	conteúdo de moderador
### GET	
	/api/test/admin	conteúdo de administrador