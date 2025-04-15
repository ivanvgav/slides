---
title: Silogismo Categórico
subtitle: "Unidad 4 y Capítulo 5 de (Zeballos y Cardozo, 2022)"
author: "Prof. Gavriloff, Ivan Vladimir"
date: "`{r} Sys.Date()`"
output:
  html:
    meta:
      css: ["@default", "@snap", "@key-buttons", "@callout", "@heading-anchor"]
      js: ["@snap", "@center-img","@heading-anchor", "@callout"]
    options:
      toc: false
      number_sections: true
vignette: >
  %\VignetteEngine{litedown::vignette}
  %\VignetteIndexEntry{Making HTML Slides with the litedown Package}
---

## Introducción al silogismo

Vamos a hacer un pequeño *stop* en la lógica proposicional

---
<!--# class="middle center" -->

![Aristóteles](https://www.superprof.cr/blog/wp-content/uploads/2022/06/z1.jpg) 

---
<!--# class="middle center" -->
Aristóteles sistematizó la la Lógica en su *Órganon*

Creador del sistema de lógica denominado silogista o lógica tradicional

---
<!--# class="middle center" -->
Su lógica trabaja con juicios categóricas o proposiciones categóricas 

---
<!--# class="middle center" -->
## Juicios (proposiciones) categóricos

Definición:

> "[...] el discurso enunciativo y perfecto que expresa un juicio
> y significa lo verdadero o lo falso"

Ej: Pedro es mayor de edad

Ej: Pedro no es mayor de edad

---
<!--# class="middle center" -->
::: callout-important

> Una proposición categórica afirma o niega simplemente
> su verificación no se encuentra sometida a condicionamiento
> o incertidumbre alguna (Zeballos y Cardozo 2022, 137) 

:::

---
<!--# class="middle center" -->
## Estructura básica de una proposición categórica

> $S\ es\ P$

Donde $S$ es el sujeto de la proposición,
$P$ es el predicado de la proposición
y "es" es la cópula

---
<!--# class="middle center" -->

Las proposiciones categóricas se pueden analizar a través de:

Cantidad

Cualidad

---
<!--# class="middle center" -->
### Cualidad
Se analiza a la proposición en función relacional de la cópula:

Afirmativas

Negativas

EJ: Ivan es tucumano

EJ: Ivan no es ruso

---
<!--# class="middle center" -->
### Cantidad
Se analiza a la proposición en relación a la cantidad de objetos sujetos a la proposición

La combinación de cualidad y cantidad lleva a considerar a las
formás típicas de proposiciones categóricas

EJ: "**Todos** los perros ladran"

EJ: "**Ningún** pez es mamífero"

EJ: "**Algunos** docentes son ruidosos"

EJ: "**Algunos** bailarines **no** son torpes"

---
<!--# class="middle center" -->
## Cuantificadores
Son los términos que encontramos en los ejemplos:
"Todos", "Ningún", "Algún", "Algún ... no es"

Se clasifican:

Universales: "Todos", "Ningún"

Particulares: "Algún", "Algún ... no es"

---
<!--# class="middle center" -->
### Tabla de las proposiciones categóricas

| Símbolo | Forma | Cantidad | Cualidad |
|:-----:|:-----:|:-----:| :------: |
| A | $Todos\ los\ S\ son\ P$ | Afirmativo | Afirmativa | 
| E | $Ningún\ S\ es\ P$ | Afirmativo | Negativo |
| I | $Algún\ S\ es\ P$ | Negativo | Afirmativa | 
| O | $Algún\ S\ no\ es\ P$ | Negativo | Negativo | 
---
<!--# class="middle center" -->
## Distribución de los términos
El sujeto y el predicado pueden ser considerados como clases

Para cada una de las proposiciones categóricas los términos
van a ser tomadas total o parcialmente

| Símbolo | Forma | Distribuido total en $S$ | Distribuido total en $P$ |
|:-----:|:-----:|:-----:| :------: |
| A | $Todos\ los\ S\ son\ P$ | Si | No |
| E | $Ningún\ S\ es\ P$ | Si | Si |
| I | $Algún\ S\ es\ P$ | No | No |
| O | $Algún\ S\ no\ es\ P$ | No | Si |

---
<!--# class="middle center" -->
### Ejemplos

Todos los futbolístas corren

Ningún juez es infalible

Algunos estudiantes son jóvenes

Algunos tucumanos no saben manejar

---
<!--# class="middle center" -->
## Cuadro tradicional de oposición
![]()

---
<!--# class="middle center" -->
Ya contamos con las herramientas necesarias para ver cómo Aristóteles trabajó los razonamientos

---
<!--# class="middle center" -->
## Silogismo categórico
Consta:

Tres proposiciones categóricas

Tres términos

---
<!--# class="middle center" -->
### Términos
Termino Mayor: predicado de la conclusión, representado por la $P$

Término menor: sujeto de la conclusión, representado por la $S$

Término medio: no aparece en la conclusión, conecta las dos premisas
representado por la $M$

---
<!--# class="middle center" -->
### Proposiciones en el silogismo categórico
Premisa Mayor: contiene al término mayor, sea como sujeto o predicado

Premisa Menor: contiene el término menor, sea sujeto o predicado

Conclusión

---
### Ejemplo de silogismo

Ningún pesimista es extrovertido

Algunas personas extrovertido son estudiantes

**Algunos estudiantes no son pesimistas**

---
<!--# class="middle center" -->
### Figuras del silogismo

Las figuras nos permiten analizar como se encuetran distribuidos los términos en el silogismo

Quien determina la figura es el $término\ medio$:

**Primera** figura: $S$ en la premisa mayor y $P$ en la premisa menor

**Segunda** figura: $P$ en las dos premisas

**Tercera** figura: $S$ en las dos premisas

**Cuarta** figura: $P$ en la premisa mayor y $S$ en la premisa menor

---
<!--# class="middle center" -->
### Modo del silogismo
El modo es la combinación posible de las proposiciones categóricas dentro del silogismo

Recordemos que sus formas son $A, E, I, O$

Teniendo en cuenta las posibilidades en las premisas y conclusión tenemos **64 modos**

Si les sumamos las figuras nos quedaría un total de **256** formas de silogismo

::: callout-important

*Modo + Figura = Forma lógica del silogismo*

:::

---
<!--# class="middle center" -->
## Determinación de validez de los silogismos
Dentro de las 256 tenemos formas válidas e inválidas

Para poder determinar tenemos que hacer uso de las reglas del silogismo
que nos indicarán si es válido o no el mismo


::: callout-important

Para que sea válido el silogismo **debe** cumplir *todas* las reglas

:::

---
<!--# class="middle center" -->
### Reglas de los términos

1. El silogismo consta de solo tres términos: mayor, medio y menor
1. El término medio no debe figurar en la conclusión
1. El término medio debe ser tomado al menos una vez en toda su extensión
1. Los términos de la conclusión no pueden tener más extensión que sus
   correspondientes en las premisas

---
<!--# class="middle center" -->
### Reglas de los juicios
1. De dos premisas negativas no se infiere conclusión alguna
1. De dos premisas particulares no se infiere conclusión alguna
1. De dos premisas afirmativas no se infiere conclusión negativa
1. La conclusión debe seguir la parte más debil

::: callout-note
*Se entiende lo más debil:*

*lo particular en relación a lo universal,*

*lo negativo en relación a lo afirmativo*
:::

