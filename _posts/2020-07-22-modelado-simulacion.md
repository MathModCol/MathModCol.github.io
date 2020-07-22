---
layout: post
title: "Modelado y Simulación"
author: "Alexander LR"
categories: journal
tags: [documentation,intro]
image: 
---
Es tomar aproximaciones _(modelos)_ del mundo real para resolver problemas.

Mediante una _simulación_ podemos hacer observaciones del modelo para distintas condiciones.

Luego _analizamos_ los resultados de las simulaciones para validar, hacer recomendaciones para futuras simulaciones, o concluir.

Finalmente, _compartimos_ nuestras conclusiones. Esto incluye visualizar datos, escribir un reporte, hacer presentaciones.

# Modelos matemáticos
Nosotros vamos a modelar sistemas. 

Un **sistema** es una colección de elementos, partes, o agentes, la cual produce resultados que no se pueden obtener mediante las partes solas.

Ejemplo: una persona no puede formar un país.

Nuestra herramienta van a ser los modelos matemáticos.

Un **modelo matemático** es una representación de un sistema mediante lenguaje matemático. Usualmente fórmulas. 

Hay varias formas de estudiar un sistema
1. el sistema real vs un modelo del mismo. 
2. un modelo físico vs un modelo matemático.
3. una solución analítica vs una solución numérica.

Por ejemplo 
1. Hechos históricos vs ideas sobre la historia.
2. Prototipo vs modelo en MATLAB del mismo.
3. Separación de variables vs método de Euler. 

## ¿Por qué hacer modelos matemáticos?
El objetivo de hacer modelos matemáticos es para resolver un problema. 

Por ejemplo: 
1. Ventiladores en túneles de Praga. 
2. Optimización del tráfico. 
3. Definir políticas en medio de una pandemia.

<div style="text-align:center"> 
<img src="./../assets/img/Prague.jpg"
     style= "max-width=600px;"/>
     </div>

Un modelo depende del problema a resolver. Si uno se enfoca mucho en las matemáticas, programación del modelo, puede obtener algo que es muy bonito pero poco útil. 
Por otro lado, el modelo puede llegar a ser muy simple y no capturar la información que nos permite resolver el problema en el que estamos interesados. 

Encontrar este punto requiere de mucha práctica y conocimiento. 

_"De aquí en adelante el modelado es más arte que ciencia. "_

<div style="text-align:center"> 
<img src="./../assets/img/art.jpg"
     style= "max-width=600px;"/>
     </div>



## Pasos para construir un modelo matemático

1. Lo primero es definir claramente cuál es el _Problema_. En este momento uno define cuál es el sistema que quiere tratar. 

2. Segundo, _construir un modelo_. Inicialmente uno asume cosas sobre el sistema. Esas suposiciones suelen convertirse en ecuaciones. Y estas ecuaciones son nuestro modelo matemático. Existen otras formas de dar un modelo matemático que no son solo ecuaciones por ejemplo mediante un programa. 

3. Tercero, _resolver el modelo_. En este paso nosotros encontramos una solución a las ecuaciones que fueron propuestas en el paso anterior. Hacemos simulaciones para encontrar la información que buscamos.

4. Cuarto, _validar el modelo_. Con los resultados del paso anterior revisamos si nuestro modelo tiene sentido, si está resolviendo la pregunta que nos estamos haciendo, y si podemos mejorarlo.

5. Quinto, iteramos. Basados en el análisis anterior podemos hacer cambios en nuestro modelo o en el método de cálculo. Normalmente, tratamos de tener un modelo lo más simple posible. 

Es fácil perderse en estos pasos. Usualmente uno se enfoca mucho en los pasos 2 y 3. Es importante tener en cuenta todos los pasos a la hora de trabajar. 

Uno no sabe (ni puede saberlo) todo. Existen problemas muy complejos para los cuales es, no solo necesario, sino imprescindible trabajar en un equipo con profesionales de distintas disciplinas. Está bien pedir ayuda. 

Lo más probable es que fuera de la academia, se encuentren con problemas que requieran de esta colaboración.
