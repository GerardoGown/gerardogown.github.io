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


# ¿Que es C++?


**C++** tiende a ser la razon por la que cerca de la mitad de los ingenieros en sistemas en latinoamerica se graduan sin saber programar.

Tambien es uno de los primeros lenguajes de programacion asi mismo es uno de los lenguajes mas robustos y usados en el mundo, en C++ esta muy probablemente programado el sistema operativo en el que estas leyendo esto, ya que es un lenguaje multiplataforma, que se puede utilizar para crear aplicaciones de alto rendimiento: sistemas operativos, navegadores, videojuegos, aplicaciones artísticas, etc.

C++ fue creado a mediados de los años 80 por el danes **Bjarne Stroustrup**, este lenguaje se creo con la intencion de que fuera una extencion del lenguaje C para que pudiera ser multiparadigma*(contiene los paradigmas de programacion y es orientado a objetos)*, asi que en gran medida este lenguaje de programacion esta basado en C.

<br>

## Estructura basica de C++

Un programa en C++ en una coleccion de comandos o sentencias que en distintas ocasiones nos va a permitir hacer llamadas directas al sistema operativo, ya que tiene un acceso directo a la memoria, que ademas controla el usuario, tambien para crear datos complejos, relacionar datos complejos, implementar patrones de diseño etc. Aqui abajo les dejo como es la estructura basica en C++ y posteriormente explicare que hace cada linea de codigo

![Struc Basic](/assets/images/IntroduccionC++-images/StrucBasic.png)


> include iostream

**Linea 1:** C++ ofrece varios encabezados, `#include <iostream>` es uno de muchos, forma parte de la libreria STL que contiene los algoritmos estandar, este es quiza la mas usada e importante (aunque no indispensable)

> using namespace std;

**Linea 3:** el `using namespace std;` namespace en una colección nombres o identificadores relacionados *(funciones, clases, variables)* que ayudan a separar estos identificadores de identificadores similares en otros espacios de nombres.

Los identificadores de la biblioteca estándar se definen en un espacio de nombres llamado std, algunas palabras dentro del **std** son: **cout, cin, endl** etc.

Para usar cualquier identificador que pertenezca a la biblioteca estándar std, debemos especificar que pertenece al espacio std. Una forma de hacerlo es usando el operador de resolución de alcance **::**, pero este solo nos servira en caso de querer quitar el `using namespace std;`. Por ejemplo,

```C++
    std::cout << "Hello world!";
```

Al agregar el **using namespace std;** no es necesario usar el **std::**, ya que este nor permitira usar las instrucciones mencianadas arriba *cout, cin y endl*

> int main() { return 0; }

La funcion `int main()` indica nuestra primera funcion por defecto, los corchetes `{}` indican el inicio y final de una funcion, dentro de los corchetes es donde podremos escribir codigo, todo lo que se encuentra dentro de estos mismos tambien es conocido como el cuerpo de la funcion

La línea 8, una linea de sentencia, y esta nos indica por medio del `return 0;` lo que la función debe retornar, en este caso, nos está diciendo que la función main(), deberá retornar cero cada vez que termine, en realidad la función main podría retornar cualquier cosa o incluso nada, podría retornar cualquier tipo de variable o incluso la variable numero misma, pero se ha establecido por acuerdo que siempre debería retornar 0, pues dado el caso en que retorne otro valor estando la sentencia return 0; dentro de ella, esto implicaría que hay algún error en la ejecución del programa. Aquí está la importancia de poner al main retornando un valor de tipo int.


## Documentacion de codigo

En C++ tambien se pueden agregar comentarios, los comentarios son lineas de codigo que no son tomadas en cuenta por el compilador una vez que este es ejecutado, los comentarios son de gran utilidad para poder explicar que hace una determinada parte de nuestro codigo y asi mismo pueda ser comprensible en caso de que otras personas necesiten leerlo, existen dos formas de hacer un comentario y estas no estan sujetas a restricciones de sintaxis *forma y orden en la que se debe escribir una instruccion, oracion, palabras etc.*, por lo cual seras libre de escribir lo que desees en un comentario.

<br>


## Tipos de comentarios:


**Comentarios de una sola linea:**.

Estos pueden ser colocados en cualquier parte y comienzan por un doble slash `//`, todo lo que este delante del slash se tomara como un comentario, las lineas de arriba y abajo no se veran afectadas

![Commetn C++](/assets/images/IntroduccionC++-images/comentarioUnalinea.png)

<br>


**Comentarios Multi-lineas:**. 

Al igual que los comentarios de una linea estos pueden ir en cualquier lado, su sintaxis es la siguiente, comienza con un slash seguido de un asterisco y para cerrar el comentario inicia con un asterisco y temina con un slash `7* comment here */`

![Comment C++](/assets/images/IntroduccionC++-images/comentarioMulti.png)

<br>


Muy bien, ya que conoces la estructura básica de un programa en C++, y una forma de documentar tu codigo, en las siguientes secciones vamos a ir mucho mas profundo, vamos a conocer otras nuevas estructuras y elementos usados comúnmente. Recuerda si tienes alguna duda o gustas aportar puedes mandarme un correo acerca de este contenido en particular y ayudarme a mejorar cada vez más el sitio. ¡¡Vamos ya!!.