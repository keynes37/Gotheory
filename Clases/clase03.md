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
<div class="subtitle">Cournot-Nash</div>
<div class="author">Carlos A. Yanes Guerra</div>
<div class="date">Barranquilla, 2026</div>
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
3. [Sintesis](#8)
4. [Funciones de reacción](#11)
5. [Cournot Nash](#12)
6. [Referencias](#19)

---
<!-- _class: "nobrand" -->
<!-- _backgroundImage: url('https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExY2N5ODQyeXBsa3BvYjVjNDVlMjg2eWlsMXlkYThrY3Q4OXowaDl3aiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/UhtYWgakzIwAJXZ1gK/giphy.gif') -->
<!-- _backgroundSize: cover -->
<!-- _backgroundPosition: center -->

---

# Estructura de Mercado

<div class="multicolumn" align="left"><div>

- Estudiamos **Competencia perfecta**: Muchos *compradores* y Muchos
vendedores.
- Estudiamos **Monopolio**: Muchos *compradores* y un único vendedor.
- Ahora vamos a ver el `Oligopolio`: Muchos *compradores* y unos cuantos
vendedores.


</div><div>

![](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExdGNkd3dtbHBkY20zM3ljMWt0NnFnMmwxeTNmemV5bjl3N2Q3ZTJnOSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/S4178TW2Rm1LW/giphy.gif)
</div><div>

---
# Oligopolio

<div class="multicolumn vcenter"><div>

- Es un **mercado** en que los <span style="color: #ff5500
;">productores</span>  tienen <span style="color: blue;">poder</span> de mercado.
- Sin embargo, se mantiene la competencia perfecta entre los <span style="color: blue;">demandantes</span>.
- Se producen **interacciones estratégicas** entre productores.
- la herramienta de análisis, es el **equilibrio de Nash**.

</div><div>

- Solo unas pocas **firmas** producen la mayor <span style="color: blue;">parte del mercado</span>.
- El producto puede ser no <span style="color:blue;">diferenciado </span>.
- Existen **barreras** a la entrada de nuevas empresas.
- La **condición de óptimo** se da cuando el ingreso marginal se iguala a costo marginal.


</div><div>

---
# Algunos conceptos adicionales

<div class="multicolumn vcenter"><div>

- ### No cooperativos
    - **Fijando cantidades**
        - Cournot
        - Stackelberg
    
    - **Fijando precios**
        - Bertrand
        - Liderazgo de precios                                

</div><div>

- ### Cooperativos
    - **Cártel**: Las empresas se
ponen de acuerdo.
Cooperan entre sí para
elegir un nivel de
producción donde se
maximiza el beneficio de
todas ellas.


</div><div>

---
# En sintesis

<div class="multicolumn vcenter"><div>

<div class="callout">

# Cournot

Toman decision en simultaneo <br> Deciden sobre **cantidades**.

</div>

<div class="callout">

# Stackelberg

Hay una empresa **lider** <br> Las otras son seguidoras.

</div>

</div><div>

<div class="callout success">

# Bertrand

Toman decisión en simultaneo <br> Deciden sobre <span style="color: #F56827;">precios</span> .

</div>

<div class="callout example">

# Liderazgo de precios

La empresa **lider** define <br> precio y la siguen las demas firmas.

</div>

</div><div>

---

![bg grayscale:1 opacity:0.3](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExYXlibHMxcmdzbHVuMHY1eGZ1NGc0Yzg1OGxjZXYwZ2tydmdzZWtjbyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/eid1RDCN2GjY1hAmZ0/giphy.gif)

<font size="+5"> Vamos a la <br> "**Microeconomía**"</font>

---
<!-- _class: "white-slide" -->
# Equilibrio de Cournot

<table style="border-collapse: collapse; width: 60%; margin: auto; text-align: center;">
  <caption style="caption-side: top; font-weight: bold; margin-bottom: 8px;">
    Producción de las firmas en duopolio
  </caption>
  <thead>
    <tr style="background-color: #FFCC67;">
      <th style="border: 1px solid black; padding: 8px;">
        <i><b>Decisión Firma 1</b></i>
      </th>
      <th style="border: 1px solid black; padding: 8px; color: #FE0000;">
        <b>Decisión Firma 2</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border: 1px solid black; padding: 8px;">30</td>
      <td style="border: 1px solid black; padding: 8px;">0</td>
    </tr>
    <tr>
      <td style="border: 1px solid black; padding: 8px;">20</td>
      <td style="border: 1px solid black; padding: 8px;">20</td>
    </tr>
    <tr>
      <td style="border: 1px solid black; padding: 8px;">10</td>
      <td style="border: 1px solid black; padding: 8px;">40</td>
    </tr>
    <tr>
      <td style="border: 1px solid black; padding: 8px;">0</td>
      <td style="border: 1px solid black; padding: 8px;">60</td>
    </tr>
  </tbody>
</table>

- Un conjunto resultante de niveles de producción.
- En equilibrio cada **empresa** supone la producción de su competencia.
- El proceso de maximización se da dado lo que **produce** la otra firma.

---
# Gráfico de reacción

![](../imagen/c3g1.png)

---
# Ejemplo de equilibrio

- Considere que existe la siguiente **función de demanda** :moneybag: :
$$P=30-Q$$

La cantidad que se produce por la existencia de **dos firmas** es:

$$Q=q_{1}+q_{2}$$

Asuma que el costo marginal es $Cmg_{1}=Cmg_{2}=0$, para ambas

---
# 📈 Ingreso Total e Ingreso Marginal de la Empresa (1)

Tomamos el ingreso **total** de la empresa (1):

$$
\begin{aligned}
I_{1} &= p q_{1} \\
      &= (30 - q) q_{1} \\
      &= 30 q_{1} - (q_{1} + q_{2}) q_{1} \\
      &= 30 q_{1} - q_{1}^{2} - q_{1} q_{2}
\end{aligned}
$$

Por el lado del **ingreso marginal** de la firma (1):

$$
Img_{1} = \frac{\partial I_{1}}{\partial q_{1}} = 30 - 2q_{1} - q_{2}
$$

---
# ⚖️ Condición de Producción Óptima de la Empresa (1)

Igualamos el **ingreso marginal** al **costo marginal** para despejar la forma de producción:

$$
Img_{1}: \; 30 - 2q_{1} - q_{2} = 0
$$

De donde se obtiene:

$$
\begin{aligned}
2q_{1} &= 30 - q_{2} \\
q_{1} &= \frac{30 - q_{2}}{2} \\
q_{1} &= 15 - 0.5 q_{2}
\end{aligned}
$$

---
# 🎯 Curvas de Reacción de las Firmas

Para el nivel de producto óptimo, se cumple la condición:

$$
Img = Cmg
$$

Por tanto, la **curva de reacción** de la empresa (1) es:

$$
q_{1} = 15 - 0.5 q_{2}
$$

De forma **simétrica**, la curva de reacción de la empresa (2) es:

$$
q_{2} = 15 - 0.5 q_{1}
$$

Ahora...  
solo queda **enfrentar las dos funciones** ⚔️

---
# ⚖️ Equilibrio de Cournot

El resultado de la igualación es:

$$
\begin{aligned}
q_{1} &= 15 - 0.5(15 - 0.5q_{1}) \\
q_{1} &= 15 - 7.5 + 0.25q_{1} \\
q_{1} &= 7.5 + 0.25q_{1} \\
q_{1} - 0.25q_{1} &= 7.5 \\
q_{1}(1 - 0.25) &= 7.5 \\
q_{1}(0.75) &= 7.5 \\
q_{1} &= \frac{7.5}{0.75} = 10
\end{aligned}
$$

Por la **simetría** del modelo, la producción de cada firma será:

$$
q_{1} = q_{2} = 10
$$

---
# ⚖️ Equilibrio de Cournot

El mercado completo es:

$$
q = 20
$$

Con un **precio de** <span style="color:blue;">\$10</span> 💰

### 💬 Reflexiones finales

- ➡️ En los mercados siempre sobrevivirán aquellos empresarios que **innovan constantemente** e **invierten en reducir costos de producción**.  

- ➡️ Los mercados son **instituciones eficientes** para asignar bienes y recursos, pero **no lo son todo**.  
  *Pendientes del libre mercado.* 💡

---
<!-- _class: "black-slide" -->
<center>

![bg bluescale:1 opacity:0.6](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExbzU3NDByc2EyeTBoZDhueGdzbGtsc2txZXE1dzBlNjN0OHR1dDJqayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xT0xelpBUyVmjxqGTC/giphy.gif)

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
