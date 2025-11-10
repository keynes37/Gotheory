---
title: Introducción a la Teoría de Juegos
author: Carlos A. Yanes Guerra
description: Curso de Economía - Universidad del Norte
keywords: [Marp, MarpX, Sparta, Teoría de Juegos, Economía]
header: Departamento de Economía
footer: "[Click para el inicio](#3)"

marp: true
theme: sparta
paginate: true
transition: fade
size: 16:9
lang: es
math: mathjax
---

<!-- _class: "title-academic" -->
<!-- _backgroundColor: white -->

![bg left:35%](../imagen/sparta1.png)

<div class="title">Introducción a la Teoría de Juegos</div>
<div class="subtitle">Estrategías Mixtas</div>
<div class="author">Carlos A. Yanes Guerra</div>
<div class="date">Barranquilla, 2025</div>
<div class="organization">Universidad del Norte - Departamento de Economía</div>

---
<!-- _class: title -->

![bg opacity:0.215 grayscale:1](../imagen/leonidas.png)

# Curso de teoría de **Juegos** 

## Microeconomía II | **Uninorte**

---
<!-- _class: toc  -->

1. [Inicio](#1)
2. [Contenido](#3)
3. [Juego Bertrand](#5)
4. [Juegos Mixtos](#11)
5. [Valor Esperado](#16)
6. [Equilibrio Mixto](#19)
7. [Referencias](#24)

---
<!-- _class: "nobrand" -->
<!-- _backgroundImage: url('https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmtyOXVleWE0ajF0MGgwMW05dWxmY2ZqdW1xY2tza2tobXYyZHN0OSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/jWK3ykVYW9XFjySTTy/giphy.gif') -->
<!-- _backgroundSize: cover -->
<!-- _backgroundPosition: center -->

<p style="font-size: 65px; color: red;">Preguntas</p>

---


<!-- _class: chapter -->

![bg grayscale:1 opacity:0.3](https://media.licdn.com/dms/image/v2/C4E12AQGuXnUaP0ymow/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1520166960359?e=2147483647&v=beta&t=b1EVJmF305CqkUQVLQ9z_uAdIa0lCo7PWGqGJyd0o60)

# Optimización
## Juego **Bertrand** 

---
# Modelo de Bertrand

<div class="multicolumn vcenter"><div>

- Su exponente **Joseph Bertrand** (1883).

- El producto es `homogéneo`. En lugar de elegir que *cantidad* a producir, las firmas eligen son **precios**.

</div><div>

- El mercado tiende a ser mas `reactivo` y **agresivo**.

</div></div>

---
# Caso Bertrand de Empresa


- Usamos una función de demanda de **mercado**:
  
  $$
  P(Q) = 60 - Q
  $$

- El **costo marginal** es idéntico para ambas firmas, y se asume que es de \$6:
  
  $$
  Cmg_{1} = Cmg_{2} = 6
  $$

- A partir de esto, podemos hacernos varias preguntas:

  **¿Cuál es el equilibrio de Nash?**  
  **¿Qué precio debe elegir cada firma?**

---
# Equilibrio del Mercado

- Cada firma produce hasta el punto en que su **precio es igual al costo marginal**:

  $$
  P = Cmg
  $$

- Usando la función de demanda:
  
  $$
  Q = 60 - P
  $$

- Si $Cmg = 6$, entonces:
  
  $$
  Q = 54 \quad \Rightarrow \quad q^{*}_{1} = q^{*}_{2} = 27
  $$

- La cantidad **total** en el mercado es $Q = 54$.

- El **beneficio** para cada firma es:
  
  $$
  \pi_i = 0
  $$

---
# Nociones

- En equilibrio, las **firmas** producen eficientemente, pero no obtienen beneficios económicos.

- Esto refleja una **competencia perfecta** en un modelo de `Duopolio` pero con precios iguales al costo marginal.

---
# Forma Normal para Bertrand

![](../imagen/c4g3.png)

Donde $\pi \in \left \{ 0, \infty^{+} \right\}$, cualquier precio menor que el que cobre la **competencia** genera múltiples beneficios.

---

<!-- _class: chapter -->

![bg grayscale:1 opacity:0.3](https://media.licdn.com/dms/image/v2/C4E12AQGuXnUaP0ymow/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1520166960359?e=2147483647&v=beta&t=b1EVJmF305CqkUQVLQ9z_uAdIa0lCo7PWGqGJyd0o60)

# Lo de Probabilidad
## Veamos **algo** adicional


---
# Juegos Mixtos

- Observe el siguiente juego **matching pennies**

![](../imagen/c4g1.png)


- Este tipo de **juegos** no tiene *equilibrio* de Nash ni de ningún equilibrio aprendido hasta el momento.

---
<p style="color: blue; font-size: 5.2rem; text-align: center;">
  ¿ <span style="color: red;">Entonces</span> <span style="color: red;">que</span> hacemos <span style="color: red;">?</span>
</p>

---
# Respuesta

Para el caso planteado, $J_1$ querrá jugar **CARA** si piensa que $J_2$ también lo hace.

- Sin embargo, $J_2$ jugará **CARA** si cree que $J_1$ juega SELLO. Así, $J_1$ debe hacer creer a $J_2$ que jugará SELLO.

- Como no existe coordinación y no será fácil engañar al otro jugador racional, quizás lo mejor que puede hacer cada jugador es hacerlo de forma `aleatoria`.

---
# Estrategías Mixtas

- De hecho, aunque existan Equilibrios de Nash en estrategias puras, quizás los jugadores puedan tener estrategias que jugarán con cierta probabilidad.

- Este tipo de estrategias las denominaremos *estrategias mixtas*: es decir, un jugador puede jugar un perfil de estrategias con cierta probabilidad.

- El concepto de **Equilibrio de Nash** se extiende a mixtas de tal forma que sea un perfil de estrategias $S = (s_{1}, s_{2}, \dots, s_{n})$, donde $S_{i} \in \triangle S_{i}$ para cada jugador $i$. $s$ es un EN en estrategias mixtas si y solo si:
    
$$u_{i} \left( s_{i}, s_{-i} \right) \geq u_{i} \left( s'_{i}, s_{-i} \right) \quad \forall \; s'_{i} \in S \quad \text{y para cada jugador} \; i$$

- La estrategía $s_{i}$ es la mejor respuesta para cualquier estrategia y jugador $i$.

---

<!-- _class: chapter -->

![bg grayscale:1 opacity:0.3](https://media.licdn.com/dms/image/v2/C4E12AQGuXnUaP0ymow/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1520166960359?e=2147483647&v=beta&t=b1EVJmF305CqkUQVLQ9z_uAdIa0lCo7PWGqGJyd0o60)

# Equilibrio Mixto
## Uso del **Valor** Esperado

---
# Valor Esperado

> El valor esperado es un concepto fundamental en la teoría de probabilidad y la estadística. Se refiere a la media ponderada de todos los posibles resultados de un experimento aleatorio, donde cada resultado se pondera por su probabilidad de ocurrir. 

- Matemáticamente, el valor esperado $E[X]$ de una variable aleatoria discreta $X$ se define como:

$$E[X] = \sum_{i=1}^{n} x_i P(x_i)$$
    
Donde: $x_i$ son los posibles valores de la variable aleatoria $X$, $P(x_i)$ es la probabilidad de que el valor $x_i$ ocurra, La suma se realiza sobre todos los posibles valores de $X$.

---
# Valor Esperado

- El `valor esperado` tiene diversas interpretaciones según el contexto. En economía, por ejemplo, se interpreta como la cantidad promedio de un valor que se espera obtener en un experimento repetido bajo condiciones de incertidumbre.

---
<!-- _class: chapter -->

![bg grayscale:1 opacity:0.3](https://media.licdn.com/dms/image/v2/C4E12AQGuXnUaP0ymow/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1520166960359?e=2147483647&v=beta&t=b1EVJmF305CqkUQVLQ9z_uAdIa0lCo7PWGqGJyd0o60)

# Equilibrio Mixto
## En teoría de **Juegos**

---
# Estructura del Juego Mixto

![](../imagen/c4g2.png)

> P y Q vienen a ser las creencias de lo que posiblemente va jugar el otro jugador.

---
# Qué hace el **Jugador 1**?

- Este jugador hace lo siguiente:

  - Enfrentar estrategía **CARA** vs **SELLO**:
     $$1(Q)+(-1)(1-Q) \geq (-1)(Q)+(1)(1-Q)$$
  - Cuando halla esto encuentra que:
     $$\begin{align*}
         Q-1+Q \geq & -Q + 1 - Q\\
         2Q-1 \geq & -2Q +1 \\
         Q \geq & \frac{2}{4} \Rightarrow Q \geq \frac{1}{2}
     \end{align*}$$

---
# Función de **reacción** Firma 1

De aquí hay que tener en cuenta `lo mejor` que haga el otro jugador. (*La interpretación es clave acá*).

$$\begin{equation*}
        FR_{1}=\left\{\begin{matrix}
P = 1 & \text{si} \; Q> \frac{1}{2} \\ 
P \in \left[0,1 \right] \frac{1}{2} & \text{si y solo si estrategia} \; Q=\frac{1}{2} \\ 
P=0 & \text{si} \; Q < \frac{1}{2}
\end{matrix}\right.
    \end{equation*}$$

*El jugador 1 siempre jugará CARA si sabe que el otro jugador tiene alta probabilidad de jugar CARA.*

---
<!-- _class: "black-slide" -->
<center>

![bg bluescale:1 opacity:0.6](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGhueDJuMnc4MzN1b3NzbGZwMWtjeXByM2RxZTFoZXVoM2UydXllYSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/dLrXrKZXPHrmWctsqk/giphy.gif)

</center>

---

# Referencias

<div class="multicolumn"><div>

1. OSBORNE, Martin J.; RUBINSTEIN, Ariel. **A Course in Game Theory**.  
   Cambridge, Massachusetts: MIT Press, 1994.

2. DIXIT, Avinash K.; SKEATH, Susan; REILEY, David H. **Games of Strategy**.  
   5ª edición. New York: W. W. Norton & Company, 2020.

3. WATSON, Joel. **Strategy: an introduction to game theory**.  
  3ª edición. New York: W. W. Norton & Company, 2016.

4. GIBBONS, Robert. **A Primer in Game Theory**.  
   New York: Harvester Wheatsheaf, 1992.


</div><div>

6. STRAUB, Paul G. **Theoretical Foundations of Game Theory**.  
   New York: Springer, 2022.

7. BINMORE, Ken. **Playing for Real: A Text on Game Theory**.  
   Oxford: Oxford University Press, 2007.

8. TUCKER, Albert W. **A Two-Person Dilemma**.  
   In: Kuhn, Harold W.; Tucker, Albert W. (Eds.). *Contributions to the Theory of Games, Vol. 1.*  
   Princeton: Princeton University Press, 1950.

9. SAFNER, Ryan. **Lecture Notes on Game Theory**.  
    Hood College, Department of Economics, 2021.  
    Disponible en: [https://ryansafner.com](https://ryansafner.com)

</div></div>
