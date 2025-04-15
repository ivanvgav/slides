---
title: "Lógica"
subtitle: "Lógica proposicional"
---
# Lógica

Gavriloff, Ivan Vladimir
Facultad de Derecho y CS. Sociales - UNT - 2025

---

Ya contamos con las nociones preliminares para trabajar en lógica

---

Ahora bien,

## ¿Qué es la lógica?
### ¿Cuál es su objeto de estudio?
#### ¿Por qué estamos estudiando esta materia?

---

Disciplina formal que estudia los *$razonamientos$

---

No nos interesa *cómo* se forma el razonamiento en nuestras mentes

No nos interesa el *contenido* de los elementos del razonamiento

---

Estudiamos la $forma$ del razonamiento

Nos interesamos por la *estructura formal del razonamiento*

---

### Estructura preliminar de todo razonamiento

$P_{1}, P_{2}, ... , P_{n} \Rightarrow C$

Donde las $P$s son las *premisas*, $C$ es la conclusión

y la "$\Rightarrow$" es la relación de consecuencia lógica

---
# Lógica proposicional

---

Lenguaje artificial para poder formalizar los razonamientos

---

## Elementos que conforman el cálculo proposicional

---

### Variables proposicionales:

Nos permiten formalizar las proposiciones

Ejemplos:

$p, q, r, s, t, ...$

---

### Constantes proposicionales
### Conectivas lógicas

---

## Conjunción
Representa el "y"; "pero"

Se simboliza mediante los siguientes signos: $\bullet$ o $\land$

Ejemplo:

"Juan estudia y toca la guitarra"

$p \land q$

---

## Disyunción
Representa el "o"; "o bien..., o bien"

Se simboliza mediante el siguiente signo: $\lor$

Ejemplo:

"O vamos a la clase o vamos a tomar un café"

$p \lor q$

---

## Condicional
Representa el "Si...entonces..."

Se simboliza haciendo uso de los siguientes signos: $\supset$ o $\rightarrow$

Ejemplo:

"Si estudias todo el libre, entonces vas a aprobar el parcial"

$p \supset q$

---
## Bicondicional
Representa el "si y solo si"

Se simboliza con los siguientes signos: $\equiv$ o $\leftrightarrow$

Ejemplo:

"Vas a poder irte de vacaciones si y solo si apruebas todas las materias"

$p \equiv q$

---
### Negación
Representa el "no"; "no es cierto que..."; "no es verdadero que..."

Se simboliza con los siguientes signos: $\neg$ o $\sim$

Ejemplo:

"Hoy no vamos a ir al cine"

$\sim p$

---
## Signos auxiliares
Son aquellos signos que nos permiten delimitar el alcance de las conectivas

Estos son los paréntesis, corchetes y llaves: $( ; ); [ ; ]; \{; \}$

---

Ejemplo:

"Si terminamos temprano, saldremos por un café y tomaremos el colectivo tranquilo"
### $p \supset q \land r \neq p \supset (q \land r)$

---
## Tabla de verdad de las conectivas

| $p$ | $q$ | $p \bullet q$ | $p \lor q$ | $p \supset q$ | $p \equiv q$ |
| :-: | :-: | :-----------: | :--------: | :-----------: | :----------: |
| $V$ | $V$ |      $V$      |     $V$    |      $V$      |     $V$      |
| $V$ | $F$ |      $F$      |     $V$    |      $F$      |     $F$      |
| $F$ | $V$ |      $F$      |     $V$    |      $V$      |     $F$      |
| $F$ | $F$ |      $F$      |     $F$    |      $V$      |     $V$      |

