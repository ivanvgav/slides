---
title: Tablas de verdad
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

# Tablas de verdad
<!--# class="middle center" -->

Mecanismo de decisión para determinar si la fórmula es:

Una tautología

Una contradicción

Una función de verdad o fórmula contigente

## A tener en cuenta
<!--# class="middle center" -->

Cantidad de proposiciones de la fórmula

Recordar que hay solo 2 valores de verdad

## Tablas de verdad de las conectivas
<!--# class="middle center" -->

| -   | -   | Negación | Conjunción  | Disyunción |    Condicional    | Bicondicional |
| --- | --- | -------- | :---------: | :--------: | :---------------: | :-----------: |
| $p$ | $q$ | $\neg p$ | $p \land q$ | $p \lor q$ | $p \rightarrow q$ | $p \equiv q$  |
| $V$ | $V$ | $F$      |     $V$     |    $V$     |        $V$        |      $V$      |
| $V$ | $F$ | $F$      |     $F$     |    $V$     |        $F$        |      $F$      |
| $F$ | $V$ | $V$      |     $F$     |    $V$     |        $V$        |      $F$      |
| $F$ | $F$ | $V$      |     $F$     |    $F$     |        $V$        |      $V$      |

## Pro tips
<!--# class="middle center" -->

Recordar siempre la fórmula $2^n$ donde $n$ es la cantidad de proposiciones de la fórmula

Recordar de ir dividiendo en $2$ hasta llegar a $1$ para poder saber cuántos valores intercalar para cada proposición

## Ejercicios
<!--# contenteditable -->

1. Democracia signiﬁca un modo de vida en el que la libertad y la justicia están presentes.
2. Las teorías cientíﬁcas no contienen conceptos que denoten *qualia*.
3. No es cierto que la luna no es blanca.
4. "Si sigues cumpliendo años, acabarás muriéndote" (Groucho Marx)
5. Si le regañas, entonces, si se molesta se marchará.
6. O estoy en la facultad de derecho o no estoy en la facultad de derecho.
7. Ivan camina y no camina.
