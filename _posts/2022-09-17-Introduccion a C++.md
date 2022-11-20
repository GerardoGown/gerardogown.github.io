---
layout: single
title: Introduccion a la Programacion - C++
excerpt: "Bienbenidos a este curso de C++, en esta area les enseñare lo basico, donde programaremos nuestra primera linea de codigo, veremos la estrucutra por defecto y que hace cada parte parte."
date: 2022-09-18
classes: wide
header:
  teaser: /assets/images/IntroduccionC++-images/IntroductionC++.jpg
  teaser_home_page: true
categories:
  - Programacion
tags:  
  - C++ 
---

# contenido
* ¿Que es C++?
* Estructura basica de C++
* Documentacion del Codigo
* Nuestra primera linea de codigo

<br>

# ¿Que es C++?


**C++** tiende a ser la razon por la que cerca de la mitad de los ingenieros en sistemas en latinoamerica se graduan sin saber programar.

Tambien es uno de los primeros lenguajes de programacion asi mismo es uno de los lenguajes mas robustos y usados en el mundo, en C++ esta muy probablemente programado el sistema operativo en el que estas leyendo esto, ya que es un lenguaje multiplataforma, que se puede utilizar para crear aplicaciones de alto rendimiento: sistemas operativos, navegadores, videojuegos, aplicaciones artísticas etc.

C++ fue creado a mediados de los años 80 por el danes **Bjarne Stroustrup**, este lenguaje se creo con la intencion de que fuera una extencion del lenguaje C para que pudiera ser multiparadigma que significa que contiene los paradigmas de programacion y es orientado a objetos, asi que en gran medida este lenguaje de programacion esta basado en C.

<br>

## Estructura basica de C++

Un programa en C++ en una coleccion de comandos o sentencias que en distintas ocasiones nos va a permitir hacer llamadas directas al sistema operativo, ya que tiene un acceso directo a la memoria y que ademas controla el usuario, tambien nos sirve para crear datos complejos relacionar estos mismos datos, implementar patrones de diseño etc.
Aqui abajo les dejo como es la estructura basica en C++ y posteriormente explicare que hace cada linea de codigo

![Struc Basic](/assets/images/IntroduccionC++-images/StrucBasic.png)

<br>

**Linea 1:** C++ ofrece varios encabezados, `#include <iostream>` es uno de muchos, forma parte de la libreria STL que contiene los algoritmos estandar, este es quiza la mas usada e importante aunque no la mas indispensable.

**Linea 3:** El `using namespace std;` es una colección de nombres o identificadores relacionados con funciones, clases y variables que ayudan a separar estos identificadores de identificadores similares en otros espacios de nombres. Los identificadores de la biblioteca estándar se definen en un espacio de nombres llamado std, algunas palabras dentro del std son: **cout, cin, endl** etc. Mas adelante vamos a utilizar estos identificadores para crear nuestro primer codigo.

Para usar cualquier identificador que pertenezca a la biblioteca estándar std, debemos especificar que pertenece al espacio std. Una forma de hacerlo es usando el operador de resolución de alcance **::**.

**Linea 5:** La funcion `int main()` indica nuestra primera funcion por defecto, los corchetes `{}` indican el inicio y final de una funcion, tambien es conocido como el cuerpo de nuestra funcion, dentro de los corchetes es donde escribiremos nuestro codigo.

**La línea 8** es una linea de sentencia, y esta nos indica por medio del `return 0;` lo que debe de retornar la funcion, en realidad esta puede retornar cualquier valor o incluso nada pero lo mas comun es que la función main() deba de retornar cero cada vez que termine, se a establecido asi porque dado el caso en que retorne otro valor estando la sentencia de return 0 dentro de ella, esto implicaria que haya algun error en la ejecucion del programa, y ahi esta la importancia de que la funcion main retorne un valor cero.


## Documentacion de codigo

En C++ tambien se pueden agregar comentarios, los comentarios son lineas de codigo que no son tomadas en cuenta por el programa una vez que este es ejecutado, los comentarios son de gran utilidad para poder explicar que hace una determinada parte de nuestro codigo y asi mismo pueda ser comprensible en caso de que otras personas necesiten leerlo.
Existen dos formas de hacer un comentario y estas no estan sujetas a restricciones de sintaxis, la sintaxis es la forma en la que se debe escribir determinado lenguaje no solo de programacion si no tambien el español, el ingles etc. asi que podemos ser libres de escribir cualquier cosa dentro de un comentario


## Tipos de comentarios

**Comentarios de una sola linea:**.

Los comentarios de una sola linea pueden ser colocados en cualquier parte del programa y comienzan por un doble slash `//`, todo lo que este delante del doble slash se toma como un comentario y esto tampoco afecta el funcionamiento de nuestro programa es totalmente libre.
Les dejo un ejemlplo abajo.

![Commetn C++](/assets/images/IntroduccionC++-images/comentarioUnalinea.png)

<br>

**Comentarios Multi-lineas:**. 

Al igual que los comentarios de una linea estos pueden ir en cualquier lado y asi mismo tampoco afecta lo que escribas dentro de estos, la sintaxis de un comentario de varias lineas es la siguiente`/*  */`, dentro del asteriscos es donde vamos a escribir nuesto comentar, les dejo un ejemplo de esta estructura abajo.
Bastante sencillo, no ?

![Comment C++](/assets/images/IntroduccionC++-images/comentarioMulti.png)

<br>

# Nuestra primera linea de codigo

Me parece que la mejor forma de no perder el interés de los lectores de esta sección aburriéndolos con muchos conceptos y teorías, es mediante un ejemplo *(a todos nos gusta la práctica)*. Veamos entonces nuestro primer programa en C++, que aunque no es muy extenso ni complicado ni tampoco hace gran cosa, nos ayudará a establecer unas bases que resultarán muy útiles para los siguientes ejemplos que irán apareciendo durante el resto del curso. No te preocupes si no comprendes nada al principio, pues me encargaré de irte enseñando cada cosa y así estaremos mejor, si no entiendes algo o crees que me faltó explicar alguna cosa, dímelo, para eso puedes encontrar del lado izquierdo mi contacto

El programa que vamos a realizar simplemente una variable que recibira el resultante de sumar *5 + 5*, cabe resaltar que en pantalla solo se mostrara un texto seguido del resultado de la suma, la ejecución del programa será prácticamente instantánea, abajo el ejemplo: 


Muy bien, ya que conoces la estructura básica de un programa en C++, y una forma de documentar tu codigo, en las siguientes secciones vamos a ir mucho mas profundo, vamos a conocer otras nuevas estructuras y elementos usados comúnmente. Recuerda si tienes alguna duda o gustas aportar puedes mandarme un correo acerca de este contenido en particular y ayudarme a mejorar cada vez más el sitio. ¡¡Vamos ya!!.