---
title: Ejercicios de Simbolización y Tablas de verdad
author: Gavriloff, Ivan Vladimir
subtitle: "Facultad de derecho y cs. sociales - UNT - 2024"
format:
  html:
    minimal: true
    include-after-body:
      text: |
        <script src="https://cdn.jsdelivr.net/gh/rstudio/markdown@1.8/inst/resources/snap.min.js" defer></script>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/combine/gh/rstudio/markdown@1.8/inst/resources/default.min.css,gh/rstudio/markdown@1.8/inst/resources/snap.min.css">
        <style type="text/css">header{text-align: center;}</style>
---

## Recordemos la sintaxis de la lógica proposicional

**Variables proposicionales**:
$p, q, r, s, t, ...$

**Constantes proposicionales o constantes lógicas**:

*Conjunción*: "y", "pero", "aunque"
$p \bullet q$

*Disyunción*: "o", "o bien..., o bien"
$p \lor q$

*Condicional*: "Si... entonces..."
$p \rightarrow q$

*Bicondicional*: "si y solo si"
$p \leftrightarrow q$

**Símbolos auxiliares**: $( , ), [, ], \{ , \}$

## Ejercicios de simbolización
<!--# contenteditable -->

Democracia significa un modo de vida en el que la libertad y la justicia están presente

Si mi idea no es convincente, tampoco lo es la tuya

Si hablas inglés, entonces, si viajas a Estados Unidos no tendrás problemas para relacionarte

Llama o escribe si y solo si no puedes ir

## Tablas de verdad

| $p$ | $q$ | $p \bullet q$ | $p \lor q$ | $p \rightarrow q$ | $p \leftrightarrow q$ |
|:---:|:---:|:-------------:|:----------:|:-----------------:|:---------------------:|
| $V$ | $V$ |      $V$      |     $V$    |        $V$        |          $V$          |
| $V$ | $F$ |      $F$      |     $V$    |        $F$        |          $F$          |
| $F$ | $V$ |      $F$      |     $V$    |        $V$        |          $F$          |
| $F$ | $F$ |      $F$      |     $F$    |        $V$        |          $V$          |

## Ejercicios de Tablas de verdad
<!--# class="middle center" -->

<!-- $p \land q$ -->
<!---->
<!-- $\neg p \rightarrow \neg q$ -->
<!---->
<!-- $p \rightarrow (q \rightarrow \neg r)$ -->
<!---->
<!-- $p \lor q \leftrightarrow \neg r$ -->

Vamos a la pizarra

## Cosas a tener en cuenta para las tablas
<!--# class="middle center" -->

El exponente $2^n$ (donde $n$ es la cantidad de proposiciones) para ver cuantas filas tiene la tabla

Dividir el resultado de la fórmula de arriba en dos hasta llegar a 1 para saber como intercalar valores

## **¿Seguimos adelante?**
<!--# class="middle center" -->

## Razonamientos
<!--# class="middle center" -->

Secuencia de proposiciones de las cuales un conjunto (las premisas) se deriva una conclusión

$$ P_{1}, P_{2}, P_{n} \Rightarrow C$$

## Simbolización de razonamientos
<!--# class="middle center" -->

Se añaden dos elementos:

El punto y coma (;): permite separar las premisas

El siguiente conjunto de símbolos para formalizar la noción de consecuencia: $/ \therefore$

## Ejemplo
<!--# class="middle center" -->

**Si es un perro, tiene cuatro patas. Es un perro. Por lo tanto, tiene cuatro patas**

$p \rightarrow q; p / \therefore q$

## Validez y verdad
<!--# class="middle center" -->

Recordemos que la lógica se encarga de analizar la validez de los razonamientos

**Aclaración**: La noción de validez es distinta de la de verdad

## Definiciones de validez
<!--# class="middle center" -->

Semántica

Sintáctica

## Validez semántica
<!--# class="middle center" -->

> Un razonamiento es válido si y solo si todas las premisas son verdaderas,
entonces la conclusión debe ser necesariamente verdadera

La definición realiza una *restricción semántica*

El único caso que no puede darse en un razonamiento válido es el siguiente:
**todas** las premisas *verdaderas* y la conclusión *falsa*

Si todas las premisas son verdaderas, se debe *necesariamente* concluir algo verdadero

Hay una *conservación de la verdad* entre las premisas y la conclusión

## Validez sintáctica
<!--# class="middle center" -->

Un razonamiento es válido sintácticamente si y solo si la conclusión se encuentra de algún modo en las premisas

Los razonamientos que analizamos son deductivos

Los razonamientos deductivos no agregar ninguna información adicional en la conclusión

## ¿Cómo analizamos si un razonamiento es válido o no?
<!--# class="middle center" -->

Tablas de verdad

Reducción al absurdo

## Tablas de verdad para razonamientos
<!--# class="middle center" -->

Aplicamos lo mismo que hemos visto para las fórmulas proposicionales

Buscamos algo distinto a los ejercicios anteriores

--- 

<!--# class="middle center" -->

Buscamos si el razonamiento permite que todas las premisas sean $V$ y la conclusión $F$

Si lo permite, entonces el razonamiento es inválido

Si no lo permite, entonces el razonamiento es válido

## A la pizarra
<!--# class="middle center" -->

## Reducción al absurdo
<!--# class="middle center" -->

Vamos a suponer que el razonamiento es inválido

El razonamiento es *válido* si en nuestro análisis **hay** una contradicción

Si *no hay contradicción* entonces el razonamiento es inválido

## A la pizarra
<!--# class="middle center" -->

## ¿Dudas, consultas?
<!--# class="middle center" -->
