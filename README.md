<!-- 
theme: uncover
class: minimal
colorPreset: dark
_class: invert
paginate: true
_paginate: false
footer: Arthur Brugière - _July 2020_
-->

# Exploring agent based models

From laptop to world class HPC

---

<!-- 
_class: invert
-->

# Who am I ?

Let me introduce myself

---

## Arthur Brugiere

- Finished my Master at the USTH (Vietnam)

- Engineer on projects ANR ESCAPE & COMOKIT
- Working on GAMA for 2 years

- Mostly involved in _Big Data_, model exploration and _High Performance Computing_ (HPC) usage

- Should start a thesis next year

---

<!-- 
_class: invert
-->

# What's ESCAPE

**Exploring by Simulation Cities Awareness on Population Evacuation**

---

<!-- _footer: "" -->

## ESCAPE: city scale evacuation

- **Hazard**: It never sticks to the plan

- **Environment**: _Roads_ and _buildings_ turn into enemies

- **Human behavior**: _People_ do everything to make the plan fail

- **Evacuation plan**: _Organization(s)_ spend resources to help people

![bg right:31% 100%](https://i.imgur.com/oPXNraM.png)

---

<!-- _footer: "" -->

## ESCAPE Framework

![w:800](https://i.imgur.com/2rAzon3.png)

---

<!-- 
_class: invert
-->

# Why explore ?

---

Answer that kinds of questions

<br>

| What If 📥 | How To 📤 |
|:---|:---|
| An exit point is closed | Evacuate as soon as possible |
| Explosion of a factory in the Rouen industrial area | Evacuate the most non-autonomous people under resource constraints |

---

<!-- 
_footer: \\* Agent Based Model\nArthur Brugière - _July 2020_
-->

## ABM* exploration is expensive and time consuming !

**Let's do some maths :** 

For a simulation with 3 parameters with 10 values each 
10^3 = **1.000 simulations** * _repetitions_

<!-- COMOKIT -> 1000rep-->
<!--  With these 3 param -> 1 Billion simulations-->

---

## Objective : 
### Explore the entire parameter space with a minimal number of simulations

---

<!-- 
_class: invert
-->

# How to explore these models easily ?

The full self-hosted solution

---

# ![OpenMole logo](https://avatars1.githubusercontent.com/u/9074912?s=200&v=4)✖ ![Gama logo](https://avatars0.githubusercontent.com/u/1560449?s=200&v=4)

---

OpenMole provides functions to explore diversity in _input_ or _output_
<br>

| ESCAPE | OpenMole |
|---|---|
| How To | Pattern Space Exploration (PSE)  |
| What If | Origin Space Exploration (OSE) |

<!-- The PSE method is designed to cover the output space -->

---

**Explaination of the PSE**

What the _Pattern Space Exploration_ is for ?

![w:1000](https://i.imgur.com/KsvhEY8.png)

<!-- The PSE method is designed to cover the output space -->

---

**Explaination of the PSE**

How the _Pattern Space Exploration_ work ?

![w:1000](https://i.imgur.com/d1EdRsq.png)

<!-- The PSE method is designed to cover the output space -->

---

<!-- 
_class: invert
_footer: \\* HPC == High Performance Comuter\nArthur Brugière - _July 2020_
-->

# GAMA ![w:125](https://avatars0.githubusercontent.com/u/63448362) HPC

COMOKIT use-case

---

**Context**: OpenMole needs a specific virtualizator (_Singularity_) to run GAMA

**Problem**: That virtualizator is not install on the HPC

--

**Solution**: Use a custom setup to optimize parallelization run with GAMA's headless tools

---

HCP pipeline

![](https://i.imgur.com/HIwcRBa.png)

---

<!-- 
_class: invert
-->

# My PhD subject 🎓

Two main points in it

---

**Co-modeling**

Continue thesis subject from Dr. Huynh Quang Nghi*

![](https://i.imgur.com/zYkIr0t.png)

<!--
_footer: \\* Huynh, Quang-Nghi. CoModels, engineering dynamic compositions of coupled models to support the simulation of complex systems. Diss. Université Pierre et Marie Curie-Paris VI, 2016.
-->

---

**Parallelization of simulation processing**

Working on parallel multi-scale calculation, 
which may be appliable on HPC environments


---

<!-- 
_class: invert
-->

# Thanks for your attention 

Feel free to ask any questions you might have
