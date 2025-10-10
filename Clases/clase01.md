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
transition: none
size: 16:9
lang: es
math: mathjax
---

<!-- _class: "title-academic" -->
<!-- _backgroundColor: white -->

![bg left:35%](../imagen/sparta1.png)

<div class="title">Introducción a la Teoría de Juegos</div>
<div class="subtitle">Estrategia, Racionalidad y Equilibrio</div>
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
3. [Ingredientes](#7)
4. [Vamos con todo](#11)
5. [Elija](#14)
6. [Tipos de Juego](#24)
7. [Referencias](#30)

---
# Esta clase no trata de
<!-- _class: "multicolumn" -->

<div class="multicolumn vcenter" align="center">

<div>
  <img src="../imagen/f1.png" width="60%">
  <br>
  <img src="../imagen/f2.png" width="60%">
</div>

<div>
  <img src="../imagen/f4.png" width="40%">
  <br>
  <img src="../imagen/f3.png" width="80%">
</div>

</div>

---
# Si no mas bien de:

<div class="multicolumn vcenter"><div>

![h:380 drop-shadow:0,5px,10px,#00000066 center](../imagen/personas.png)

<figcaption align="center"> <i>Preguntas y preguntas</i> Interacción.</figcaption>

</div><div>

## Rol de las personas

En realidad juega roles en *diferentes* **juegos**

- Familia
- Amigos
- Compañeros de clase
- Conduciendo
- Empleador
- Reputación
- Conmigo

> Todo el tiempo usted está jugando

</div>
</div>

---
# Juegos no solo tiene que ver con **Economía**

<div class="multicolumn vcenter"><div>

- Naturaleza
- Derecho
- Deportes
- Biología
- Ciencias Políticas


</div><div>


![h:380 drop-shadow:0,5px,10px,#00000066 center](
https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExYTczdnQxaWRxazZucWQ0b2R2azNpZzAwNjlsNTgyZmcxNjFoZXY4byZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/lgeL0sh6Hg9tC/giphy.gif)

</div>
</div>

---
<!-- _class: chapter -->

![bg grayscale:1 opacity:0.3](https://media.licdn.com/dms/image/v2/C4E12AQGuXnUaP0ymow/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1520166960359?e=2147483647&v=beta&t=b1EVJmF305CqkUQVLQ9z_uAdIa0lCo7PWGqGJyd0o60)

# Ingredientes

## Lo que matemáticamente requiere
---
# Definición

- Un `juego` puede ser descrito como
$$\Gamma = (s_1,s_2, \cdots, s_n;u_1, u_2, \cdots, u_n):$$

Donde **habrá**:

1. Jugadores $i \in \{1,2,\cdots, N\}: N \geq 2$
2. Conjunto de estrategíaa $s_i \in \{S_i\}$
  - $S_i$ i es el espacio estrategico del **jugador** $i$
3. Los pagos/recompensa $u_i \in \{s_i, s_{\neg i}\}$
  - $u_i: S_i \times S \cdots S_{\neg i} \rightarrow \mathbb{R}$

---
<!-- _class: "nobrand" -->
<!-- _backgroundImage: url('https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExdnFmeWMxem9keDJxeTFlank1ejFzdTJsdDh3cHoyN3B4ODJwdmxnayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/TIRlx3Fzi1A7L2d5z7/giphy.gif') -->
<!-- _backgroundSize: cover -->
<!-- _backgroundPosition: center -->

---
# Ahora que lo he asustado

<div class="multicolumn vcenter"><div>

## Esto puede ser abstracto

- En esta clase utilizaremos algunas cosas de matemáticas, pero no va ser todo.

- No va tener ningún problema si sabe:
    - Hacer álgebra simple.
    - Calcular un promedio o un valor esperado.
    - Derivar.

- Aunque no sea así, podrá ponerse al día.

- Me voy a centrar en aplicaciones y ejemplos de **interacción estratégica**.

</div><div>

![h:390 drop-shadow:0,5px,10px,#00000066 center](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExZWZqY2VqM2I4amhsNXY1YzNmc2Y4YjZoanI3ZHN4NGVoZzM2bDFpYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3o7btPCcdNniyf0ArS/giphy.gif)


</div></div>

---
<!-- _class: chapter -->

![bg grayscale:1 opacity:0.3](https://media.licdn.com/dms/image/v2/C4E12AQGuXnUaP0ymow/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1520166960359?e=2147483647&v=beta&t=b1EVJmF305CqkUQVLQ9z_uAdIa0lCo7PWGqGJyd0o60)

# Vamos con **todo!!**

## A lo que vinimos

---

# Qué define entonces un juego?

<div class="multicolumn vcenter"><div>

![h:300 drop-shadow:0.3px,0.5px,#00000066 center](../imagen/uso.png)

<figcaption align="center">Definición de juegos.</figcaption>

</div><div>

<div class="callout danger">

# Definición

Un **Juego** es una situación en la que los *jugadores* toman **decisiones estratégicas** donde se tienen en cuenta las acciones y las respuestas de los demás.
</div>

- **Recompensa**: Pagos o utilidad 
- **Reglas**: Planes de acción que tienen los individuos para jugar.
- **Jugadores**: Personas | instituciones | naturaleza
- **Consecuencias**: Valores de resultados posibles de una interacción estratégica.   

</div></div>

---
# Vamos a empezar primero con un juego

### Actividad: A o B – tentación vs. coordinación

`Objetivo`: decidir en secreto entre A o B. Será emparejado al azar con otra persona del salón (no sabrá quien le corresponde). *El papel debe tener solo la letra que elige y su nombre y apellido*.

#### Reglas

Consecuencias de puntos (bonificación sobre el examén final):
	•	Si tú eliges A y tu pareja elige B → tú ganas +10 puntos y tu pareja 0.
	•	Si ambos eligen B → +2 para cada uno.
	•	Si ambos eligen A → +1.

---
<!-- _class: chapter -->

![bg grayscale:1 opacity:0.3](https://media.licdn.com/dms/image/v2/C4E12AQGuXnUaP0ymow/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1520166960359?e=2147483647&v=beta&t=b1EVJmF305CqkUQVLQ9z_uAdIa0lCo7PWGqGJyd0o60)

# Elija **YA!!**

## Ya veremos que pasa

---
# Ejemplo de forma normal

- Vamos a ver primero como se arma el <span style="background-color:#ffa726; padding:2px 4px;">Juego Propuesto</span>
> La forma normal de un juego es como una matriz cuadrada.

<h3 style="text-align:center; color:#000;">Jugador 2</h3>

<table style="margin:auto; border-collapse:collapse; text-align:center; font-size:22px; border:1px solid #000;">
  <tr>
    <th style="border:none;"></th>
    <th style="border:none;"></th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">A</th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">B</th>
  </tr>
  <tr>
    <th rowspan="2" style="background-color:#c62828; color:white; border:1px solid #000; padding:5px;">Jugador 1</th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">A</th>
    <td style="border:1px solid #000; width:100px;">1 , 1</td>
    <td style="border:1px solid #000; width:100px;">10 , 0</td>
  </tr>
  <tr>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">B</th>
    <td style="border:1px solid #000;">0 , 10</td>
    <td style="border:1px solid #000;">2 , 2</td>
  </tr>
</table>
<figcaption align="center"> <i>Matriz de Juego</i> forma normal.</figcaption>


---
# Por qué lo anterior es un **Juego**?

<div class="multicolumn vcenter"><div>

### Varias razones

- Hay más de un jugador.
- Existen estrategias disponibles para cada jugador.
- Los pagos se determinan conjuntamente por las estrategias elegidas.
- Usted no sabe quién es el otro jugador, pero aun así debe pensar en cómo responder a sus estrategias con las propias.

</div><div>

![h:390 drop-shadow:0,5px,10px,#00000066 center](../imagen/state1.png)

</div></div>

---

# Como resolver lo anterior

- Flujo de <span class="box">**actividad**</span> que se usa en **juegos** para responder.

<div align="center" style="margin-top:1em; font-size:1.1em;">
  <span class="box">Jugador</span>
  <span style="font-size:1.3em; margin:0 12px;">⟶</span>
  <span class="box">Qué juega?</span>
  <span style="font-size:1.3em; margin:0 12px;">⟶</span>
  <span class="box">Compare</span>
</div>

<div align="center" style="margin-top:1em; font-weight:600;">
  De tal manera que:
</div>

<div align="center" style="margin-top:0.5em;">
  <box>Toma filas</box>
  <span style="font-size:1.3em; margin:0 12px;">⟶</span>
  <box>compara los pagos</box>
  <span style="font-size:1.3em; margin:0 12px;">⟶</span>
  <box>Elige</box>
</div>

<footnote> *Nota: Cuando juega el jugador (2) la comparación la hace por columnas

</footnote>

---
# Volvamos a la **matemática**

## Estrategias estrictamente dominantes (E.E.D)

- Son aquellas estrategias que <span class="box">**sin importar**</span> que haga otro jugador (contrario), siempre su <span style="border-bottom:4px solidrgb(233, 50, 169);">Utilidad</span> es **mayor** que cualquier otra estrategia del propio jugador.

$$U(s_{i},s_{-i})>U(s^{*}_{i},s_{-i})$$

*El signo de la ***desigualdad*** es preferente* (A es mas preferido que B)
    
> Piense en que si a usted le gusta la pizza mas que la hamburguesa, siempre escogerá pizza.

---
# Resolviendo el juego

### Mire a continuación:

Elegir **A** vs elegir **B** *(sin importar que juegue el otro)* $\Rightarrow$
$$\text{Estrategia A da pagos de}\;: \color{blue}{1} \quad \color{blue}{10}$$

<center>
VS
</center>

$$\text{Estrategia B le da pagos de}\;  \color{red}{0} \quad \color{red}{2}$$

---
# Esto es

<h3 style="text-align:center; color:#000;">Jugador 2</h3>

<table style="margin:auto; border-collapse:collapse; text-align:center; font-size:22px; border:1px solid #000;">
  <tr>
    <th style="border:none;"></th>
    <th style="border:none;"></th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">A</th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">B</th>
  </tr>
  <tr>
    <th rowspan="2" style="background-color:#c62828; color:white; border:1px solid #000; padding:5px;">Jugador 1</th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">A</th>
    <td style="border:1px solid #000; width:100px;">
      <span style="color:#1565c0; font-weight:600;">1</span> , 1
    </td>
    <td style="border:1px solid #000; width:100px;">
      <span style="color:#1565c0; font-weight:600;">10</span> , 0
    </td>
  </tr>
  <tr>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">B</th>
    <td style="border:1px solid #000;">
      <span style="color:#1565c0; font-weight:600;">0</span> , 10
    </td>
    <td style="border:1px solid #000;">
      <span style="color:#1565c0; font-weight:600;">2</span> , 2
    </td>
  </tr>
</table>

<figcaption align="center"><i>Comparación Jugador 1</i> forma normal.</figcaption>

<div class="callout">

# Tip :dart:

Note que quien **mejor** pagos :moneybag: da es jugar la estrategia **A**, aunque las consecuencias no sean las deseadas. El equilibrio es individualista.

</div>

---

# Para el jugador B

<h3 style="text-align:center; color:#000;">Jugador 2</h3>

<table style="margin:auto; border-collapse:collapse; text-align:center; font-size:22px; border:1px solid #000;">
  <tr>
    <th style="border:none;"></th>
    <th style="border:none;"></th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">A</th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">B</th>
  </tr>
  <tr>
    <th rowspan="2" style="background-color:#c62828; color:white; border:1px solid #000; padding:5px;">Jugador 1</th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">A</th>
    <td style="border:1px solid #000; width:100px;">
      1 , <span style="color:#c62828; font-weight:600;">1</span>
    </td>
    <td style="border:1px solid #000; width:100px;">
      10 , <span style="color:#c62828; font-weight:600;">0</span>
    </td>
  </tr>
  <tr>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">B</th>
    <td style="border:1px solid #000;">
      0 , <span style="color:#c62828; font-weight:600;">10</span>
    </td>
    <td style="border:1px solid #000;">
      2 , <span style="color:#c62828; font-weight:600;">2</span>
    </td>
  </tr>
</table>

<figcaption align="center"><i>Pagos de jugador 2</i> forma normal.</figcaption>

<div class="callout danger">

# Qué pasó? :warning:

El jugador (2), tambien hace lo mismo y compara (*lo hace de tal manera que es vertical*). El va elegir lo **mejor** para él. En este caso va elegir **A** y el equilibrio que vamos a tener es (**A,A**)

</div>

---
# Forma Extensiva

<!-- _class: "white-slide" -->

<div class="multicolumn vcenter"><div>

### Algunos Juegos se pueden representar

- De forma de **árbol**
- Los jugadores juegan en nodos
- Puede hacerlos vertical u horizontal
- Tienen formas o algortimos para resolverlo

</div><div>

![h:300 center](../imagen/exxtensivo1.png)

</div></div>

---
<!-- _class: "white-slide" -->
# Resultados obtenidos

![h:300 center](../imagen/Rplotbar.png)


---

![bg grayscale:1 opacity:0.3](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExMTNyMTV4MWw1OWoxM3Qxdm93MHIxM3J6cTgwdzR1cjY4dGQ4Z21nciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/BYKYQ4hbRNPPO/giphy.gif)

<font size="+5">Lo anterior se conoce como <br> "**Dilema del Prisionero**"</font>



---
<!-- _class: chapter -->

![bg grayscale:1 opacity:0.3](https://media.licdn.com/dms/image/v2/C4E12AQGuXnUaP0ymow/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1520166960359?e=2147483647&v=beta&t=b1EVJmF305CqkUQVLQ9z_uAdIa0lCo7PWGqGJyd0o60)

# Tipos de Juego

## Otras formas de jugar

---

# Tipos de Juegos

<!-- _class: "white-slide" -->

<div class="callout danger">

# Juegos Cooperativos :handshake:

 Los agentes pueden **negociar contratos** vinculantes que permiten adoptar estrategias conjuntas. 
</div>

<div class="callout note">

# Juegos No Cooperativos :crossed_swords:

No es posible **negociar contratos** vinculantes. 
</div>

---

# Tipos de Juegos

<!-- _class: "white-slide" -->

<div class="callout bug">

# Juegos simultaneos :game_die:

Los agentes juegan **a la misma vez**.
</div>

<div class="callout example">

# Juegos secuenciales :trophy:

Los jugadores juegan o hacen una movida **una vez** y luego debe esperar la reacción de otro *jugador*. *Puede ver que ha hecho otro anteriormente*
</div>

---
# Juego **Secuencial**

<!-- _class: "white-slide" -->

![h:500 center](../imagen/exxtensivo2.png)

---
# Otros tipos de **Juegos**

<div class="multicolumn vcenter"><div>

![h:380](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExY3YxYXgxbmk5eWhzbnk2ZWJ4Y3V5aDA5dzJ6czA1bjRoZm40bDdnNCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ms3yqSf67KQjnXm6kN/giphy.gif)

<figcaption align="center"> <i>Juegos de tablero</i> Interacción.</figcaption>

</div><div>

Hay variedad de formas de jugar juegos.

- <span style="border-bottom:4px solid #ffa726;">Juegos de un solo momento</span>, juegos repetidos, juegos *infinitamente* repetidos.

- <span style="color:red">Juegos de confianza</span> 


</div>
</div>

---

# Otros tipos de **Juegos**

<div class="multicolumn vcenter"><div>

![h:380](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZGlvNG90MDNqbHNhMHhkem5pb2NzZzZzYjFsZmU4NWRiMW1iNmRlZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/KhZmo4Sg2vy4fux8bc/giphy.gif)

<figcaption align="center"> <i>Juegos reales</i> Suma Cero.</figcaption>

</div><div>

Hay estilos que la ganacia de un jugador es la perdida del otro

- <span style="color:red">Juegos de Suma Cero </span>

<h3 style="text-align:center; color:#000;">Portero</h3>

<table style="margin:auto; border-collapse:collapse; text-align:center; font-size:22px; border:1px solid #000;">
  <tr>
    <th style="border:none;"></th>
    <th style="border:none;"></th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">Derecha</th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">Izquierda</th>
  </tr>
  <tr>
    <th rowspan="2" style="background-color:#c62828; color:white; border:1px solid #000; padding:5px;">Delantero</th>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">Derecha</th>
    <td style="border:1px solid #000; width:100px;">-1 , 1</td>
    <td style="border:1px solid #000; width:100px;">1 , -1</td>
  </tr>
  <tr>
    <th style="background-color:#c62828; color:white; border:1px solid #000;">Izquierda</th>
    <td style="border:1px solid #000;">1 , -1</td>
    <td style="border:1px solid #000;">-1 , 1</td>
  </tr>
</table>
<figcaption align="center"> <i>Matriz de Suma Cero</i> forma normal.</figcaption>


</div>
</div>

---
<!-- _class: "references" -->

# Referencias

<div class="multicolumn"><div>

1. OSBORNE, Martin J.; RUBINSTEIN, Ariel. **A Course in Game Theory**.  
   Cambridge, Massachusetts: MIT Press, 1994.

2. DIXIT, Avinash K.; SKEATH, Susan; REILEY, David H. **Games of Strategy**.  
   5ª edición. New York: W. W. Norton & Company, 2020.

3. MYERSON, Roger B. **Game Theory: Analysis of Conflict**.  
   Cambridge, Massachusetts: Harvard University Press, 1991.

4. GIBBONS, Robert. **A Primer in Game Theory**.  
   New York: Harvester Wheatsheaf, 1992.

5. FUDENBERG, Drew; TIROLE, Jean. **Game Theory**.  
   Cambridge, Massachusetts: MIT Press, 1991.

</div><div>

6. STRAUB, Paul G. **Theoretical Foundations of Game Theory**.  
   New York: Springer, 2022.

7. BINMORE, Ken. **Playing for Real: A Text on Game Theory**.  
   Oxford: Oxford University Press, 2007.

8. TUCKER, Albert W. **A Two-Person Dilemma**.  
   In: Kuhn, Harold W.; Tucker, Albert W. (Eds.). *Contributions to the Theory of Games, Vol. 1.*  
   Princeton: Princeton University Press, 1950.

9. VON NEUMANN, John; MORGENSTERN, Oskar. **Theory of Games and Economic Behavior**.  
   Princeton, NJ: Princeton University Press, 1944.

10. SAFNER, Ryan. **Lecture Notes on Game Theory**.  
    Hood College, Department of Economics, 2021.  
    Disponible en: [https://ryansafner.com](https://ryansafner.com)

</div></div>

---

<div style="text-align:center; font-style:italic; margin-top:1em;">
Agradecimiento especial a <b>Paulo Cunha</b> por el desarrollo del entorno <b>MarpX</b>  
y a <b>Ryan Safner</b> por sus inspiradoras notas de clase sobre teoría de juegos.
</div>

---

<!-- _class: "black-slide" -->
<center>

![bg bluescale:1 opacity:0.6](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExOWQ2azI3dWNiMTJ6dnY4NzJzYTM2d3J3dXBmYTJhbW1sc2xubHNmcSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JVXU0uN1l6wdq/giphy.gif)

</center>