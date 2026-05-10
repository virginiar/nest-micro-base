<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Nest-Micro-Base

Aplicación de repaso de [Nest](https://github.com/nestjs/nest) basado en el curso de "NestJs + Microservicios: Aplicaciones escalables y modulares" de [DevTalles](https://cursos.devtalles.com/) en Udemy.

## Configuración del proyecto

1. Instalar NestJS CLI

```bash
$ npm i -g @nestjs/cli
```
2. Clonar el repositorio

3. Instalar las dependencias

```bash
$ npm install
```

4. Clonar el archivo .env.template y renombrar la copia a ```.env```.

5. Completar las variables de entorno en el archivo ```.env```.

6. Ejecutar el proyecto

```bash
$ npm run start:dev
```

## Aspectos estudiados

En esta API se trabajan los siguientes aspectos de Nest:
-	Módulos
-	Controladores
-	Servicios
-	DTOs (Data Transfer Objects)
-	Pipes
-	REST
  -	Create
  -	Update / Patch
  -	Delete
  -	Get
-	Validaciones
-	Nest CLI

## Librerías utilizadas

Para las validaciones se utilizan:

```bash
$ npm install class-validator class-transformer
```

Para la generación de UUID:

```bash
$ npm install uuid
```

Para la gestión de variables de entorno:

```bash
$ npm install dotenv
```