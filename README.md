# Proyecto Programacion Web: CleverTrip

Integrantes:
- Gustavo Hernández Cano 220791071
- Inti Martinez Flores


## Descripcion del proyecto
CleverTrip es un sistema de búsqueda de información turística inteligente, utilizando técnicas de recomendación con inteligencia artificial y filtrado por categorías, que sirva como guía turístico a los usuarios brindando sugerencias de los mejores sitios (restaurantes, hoteles, lugares de interés, etc.) basados en los gustos y preferencias del usuario en función de su ubicación actual, además de un sistema de creación de planes de viaje con el que el usuario puede organizar mejor sus actividades.

Este sistema esta planteado como una aplicacion web, la cual es programada con la ayuda del framework de AngularJS, utilizando los lenguajes de HTML, CSS y Typescript, ademas del uso de Javascript en ciertos servicios que utiliza la app, el Backend esta programado con node.js, aprovechando las ventajas que brindan los servicios de Funciones Lambda y API Gateway de AWS, mediante estos servicios se crea un sistema distribuido basado en microservicios, los cuals se encargan de realizar los movimientos en la base de datos como tambien las consultas a la API de Google.

El gestor de base de datos utilizado es Firestore de Forebase, proporcionado por Google Platform, dicho gestor nos proporciona una base de datos NoSQL con una estructura de arboles JSON, ademas de permitirnos realizar una autenticacion de cuentas para el inicio de sesion de nuestros usuarios, ademas de ofrecer un servicio de hosting para la aplicacion.

Para la IA se usa Inteligencia artificial aplicada mediante algoritmos de recomendación. Para ofrecer sugerencias personalizadas a los usuarios. Estos algoritmos pueden analizar los intereses, preferencias y comportamientos de los usuarios, así como los datos históricos, para recomendar destinos, actividades, restaurantes u otros servicios turísticos que se ajusten a sus gustos.

El algoritmo de recomendaciones de filtrado colaborativo, se basa en el comportamiento y las preferencias de un grupo de usuarios para hacer recomendaciones a un usuario en particular. Opera mediante la recopilación de preferencias o gustos de un mismo consumidor comparados con los datos suministrados por personas con patrones similares. Este algoritmo consta de dos pasos principales, primero se calcula un rango de similitud entre el usuario objetivo y otros usuarios mediante el coeficiente de correlación de Pearson, y como segundo paso se clasifican los usuarios más parecidos a el usuario objetivo para así poder recomendar elementos guardados o calificados por los usuarios más parecidos.
