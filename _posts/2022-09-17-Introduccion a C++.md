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

**C++** tiende a ser la razon por la que cerca de la mitad de los ingenieros en sistemas se gradua sin saber programar.

Tambien C++ es uno de los primeros lenguajes de programacion asi mismo es uno de los lenguajes mas robustos y usados en el mundo, en C++ esta muy probablemente programado el sistema operativo en el que estas leyendo esto, ya que es un lenguaje multiplataforma, que se puede utilizar para crear aplicaciones de alto rendimiento: sistemas operativos, navegadores, videojuegos, aplicaciones artísticas, etc.

C++ fue creado a mediados de los años 80 por el danes **Bjarne Stroustrup**, este lenguaje se creo con la intencion de que fuera una extencion del lenguaje C para que pudiera ser multiparadigma*(contiene los paradigmas de programacion y es orientado a objetos)*, asi que en gran medida C++ esta basado en C.

<br>

## Estructura basica de C++

Un programa en C++ en una coleccion de comandos o sentencias, a continuacion les mostrare la estructura basica de C++

``` C++
#include <iostream>

using namespace std;

int main() {


    return 0;
}
```

> include iostream

C++ ofrece varios encabezados, **include iostream** es uno de muchos, forma parte de la libreria STL que contiene los algoritmos estandar, este es quiza la mas usada e importante (aunque no indispensable)

> int main() {}

La funcion **int main()** indica nuestra primera funcion por defecto, los corchetes **{}** indican el inicio y final de una funcion, donde podremos escribir codigo, tambien es conocido como el cuerpo de la funcion

<br>