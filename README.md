# Proyecto Programacion Web: CleverTrip

Integrantes:
- Gustavo Hernández Cano 220791071
- Inti Martinez Flores 220790938



## Descripcion del proyecto
CleverTrip es un sistema de búsqueda de información turística inteligente, utilizando técnicas de recomendación con inteligencia artificial y filtrado por categorías, que sirva como guía turístico a los usuarios brindando sugerencias de los mejores sitios (restaurantes, hoteles, lugares de interés, etc.) basados en los gustos y preferencias del usuario en función de su ubicación actual, además de un sistema de creación de planes de viaje con el que el usuario puede organizar mejor sus actividades.

Este sistema esta planteado como una aplicacion web, la cual es programada con la ayuda del framework de AngularJS, utilizando los lenguajes de HTML, CSS y Typescript, ademas del uso de Javascript en ciertos servicios que utiliza la app, el Backend esta programado con node.js, aprovechando las ventajas que brindan los servicios de Funciones Lambda y API Gateway de AWS, mediante estos servicios se crea un sistema distribuido basado en microservicios, los cuals se encargan de realizar los movimientos en la base de datos como tambien las consultas a la API de Google.

El gestor de base de datos utilizado es Firestore de Forebase, proporcionado por Google Platform, dicho gestor nos proporciona una base de datos NoSQL con una estructura de arboles JSON, ademas de permitirnos realizar una autenticacion de cuentas para el inicio de sesion de nuestros usuarios, ademas de ofrecer un servicio de hosting para la aplicacion.

Para la IA se usa Inteligencia artificial aplicada mediante algoritmos de recomendación. Para ofrecer sugerencias personalizadas a los usuarios. Estos algoritmos pueden analizar los intereses, preferencias y comportamientos de los usuarios, así como los datos históricos, para recomendar destinos, actividades, restaurantes u otros servicios turísticos que se ajusten a sus gustos.

El sistema de recomendaciones de filtrado colaborativo, se basa en el comportamiento y las preferencias de un grupo de usuarios para hacer recomendaciones a un usuario en particular. Opera mediante la recopilación de preferencias o gustos de un mismo consumidor comparados con los datos suministrados por personas con patrones similares. Este algoritmo consta de dos pasos principales, primero se calcula un rango de similitud entre el usuario objetivo y otros usuarios mediante el algoritmo de distancia euclidiana que sirve para comparar distintos conjuntos de datos, y como segundo paso se clasifican los usuarios más parecidos al usuario objetivo para así poder recomendar elementos guardados o calificados por los usuarios más parecidos.

##Sistema
Inicio de Sesión <br>
<img width="734" alt="image" src="https://github.com/inti2001/CleverTrip_PrograWeb/assets/58715706/78da8f3f-743a-423b-93da-c830a28331d9">

Registro <br>
<img width="735" alt="image" src="https://github.com/inti2001/CleverTrip_PrograWeb/assets/58715706/3fb57de0-f1fa-4219-9294-acc3fe2bec9e">

Principal <br>
<img width="742" alt="image" src="https://github.com/inti2001/CleverTrip_PrograWeb/assets/58715706/be6e40d0-82c5-4d28-9933-58dbef3cf566">

Resultados de busqueda y filtrado <br>
<img width="605" alt="image" src="https://github.com/inti2001/CleverTrip_PrograWeb/assets/58715706/f10cd1a7-0c4f-465a-b3bc-9d3d60df457c">

Dashboard <br>
<img width="569" alt="image" src="https://github.com/inti2001/CleverTrip_PrograWeb/assets/58715706/8f33639d-a5a4-4164-816d-4146b5f42417">

Planes de viaje <br>
<img width="311" alt="image" src="https://github.com/inti2001/CleverTrip_PrograWeb/assets/58715706/77e05878-d911-4396-a055-ed9923cddfab">
<img width="310" alt="image" src="https://github.com/inti2001/CleverTrip_PrograWeb/assets/58715706/fb3104b1-b58b-4ec7-a077-81a69c8119f9">

<br>
## Guia de despliegue:
En CMD y en la carpeta del proyecto
Iniciar sesion en firebase
- firebase login

Inicializar firebase en el proyecto
- firebase init

- Seleccionar la opcion de Hostiong: Configure files for firebase hosting
- Seleccionar proyecto de firebase a utilizar

Construir proyecto
- ng build

Hacer deploy del proyecto
- firebase deploy

##Anexos
- Link de deploy: https://clevertrip-59cb1.web.app/
- Presentacion del proyecto: https://github.com/inti2001/CleverTrip_PrograWeb/blob/master/CleverTrip%20Presentacion.pptx
