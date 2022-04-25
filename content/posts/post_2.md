---
title: "¿Qué es Node JS?"
date: 2022-04-25
description: 'Explicación práctica sobre Node'
---

La página oficial de nodejs.org nos menciona que es un entorno de ejecución para Javascript construido con el motor de Javascript V8 de Chrome. Pero creo que al leerlo no es muy claro, no entendemos que es un entorno de ejecución y que tiene que ver el motor V8 de Google Chrome.

Antes de la llegada de Node, usábamos el lenguaje de Javascript para escribir aplicaciones que solamente se podían ejecutar dentro de un navegador como Google Chrome, Firefox, Opera, Safari, etc.

Ahora bien, cada navegador tiene un motor de Javascript y el trabajo de este es tomar el código y convertirlo en código que nuestra computadora o CPU pueda entender, ya que nuestra computadora no entiende el lenguaje de Javascript sino que entiende un lenguaje al que se le llama machine code o código de máquina, entonces el trabajo de estos motores es tomar el código de Javascript y convertirlo en código que la computadora pueda entender. 

Cada navegador tiene su motor de Javascript, por ejemplo, en Microsoft Edge encontramos el Motor Chakra, en Firefox tenemos SpiderMonkey y en Google Chrome el V8. Así que era dentro de los navegadores la única manera que teníamos para poder ejecutar código Javascript, 

Pero esto fue hasta el año 2009, ya que gracias al programador Ryan Dahl determino que sería bueno poder ejecutar código Javascript no solamente dentro del navegador sino fuera del navegador para así escribir código Javascript que fuera independiente del navegador.

Entonces fue que tomo el motor de Javascript de Google Chrome llamado V8, que es open source o de código abierto y lo puso dentro de un programa que el escribió con el lenguaje de programación C++ y llamo a este programa Node.

Similar a un navegador ahora Node es el entorno de ejecución para Javascript. Lo interesante de Node es que nos puede dar módulos que nos permite hacer cosas con Javascript que Javascript no puede hacer dentro del navegador.

Por ejemplo, Node nos da un módulo que nos permite con Javascript acceder a archivos en el sistema, también nos permite con otro modulo crear un servidor 
y estar escuchando peticiones.

Entonces en esencia Node es un programa que incluye el motor de Javascript V8, además de módulos adicionales que no están disponibles en el navegador. Entonces Google Chrome y Node comparten el mismo motor de Javascript pero tiene en un entorno de ejecución distinto.

La página oficial de Nodejs también nos habla de otra característica clave, no dice que Node está orientado a eventos asíncronos y diseñado para crear aplicaciones network escalables.

Para entender que son los eventos asíncronos imagínate cuando visitas un restaurante y entonces el mesero viene a tu mesa toma tu orden y luego va y se la lleva el chef y luego este mesero va a tomar la orden de otra mesa mientras el chef está preparando tu platillo así que un solo mesero puede tomar la orden de diferentes mesas, no tiene que esperar a que el chef prepare un platillo antes de tomar la orden de otra mesa.

Con este ejemplo más o menos es como funcionan las aplicaciones de Node, el mesero es como un hilo de ejecución, una red que se le asigna encargarse de diferentes peticiones y así es como un solo hilo de ejecución puede encargarse de varias peticiones.

Así que Node es un entorno controlado por eventos se ha diseñado para crear aplicaciones escalables, permitiendo establecer y gestionar múltiples conexiones al mismo tiempo. Gracias a ello, no tienes que preocuparte con el bloqueo de procesos.

Las aplicaciones de Node.js son escritas en JavaScript y la ventaja es que pueden ejecutarse en OS X, Microsoft Windows y Linux. Por ello Node ha significado un gran cambio en las tecnologías digitales de nuestro tiempo. Así que este popular entorno de programación puede utilizarse para crear aplicaciones a gran escala que necesiten soportar múltiples peticiones concurrentes.



Gracias por leer!!
