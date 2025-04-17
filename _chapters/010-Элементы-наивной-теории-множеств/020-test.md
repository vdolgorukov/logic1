---
layout: post
title: Элементы наивной теории множеств
slug: set theory
abstract: 
---


# Упражнениe 1 

{% include quiz.html 
  id="1"
  type="multiple" 
  question="Какие из утверждений ниже верны?" 
  options="$\\{a, b \\} = \\{b, a\\}$|
  $\\{a, b, b, b, b, c \\} = \\{b, a, c\\}$|
  $\langle a, b \rangle = \langle b, a \rangle$"
  answer="1|2" 
%}

# Упражнениe 2 

{% include quiz.html 
  id="2"
  type="multiple" 
  question="Пусть $X = \\{a, b \\}$, $Y = \\{a, b, c \\}$   тогда какие из утверждений ниже верны?" 
  options="$X \subseteq Y$|
  $Y \subseteq X$|
  $X = Y$|
  $X \subset Y$|
  $Y \subset X$
  "
  answer="1|4" 
%}


# Упражнениe 3

**Пусть $A = \\{a, \\{b\\}, c \\}$, тогда какие из утверждений ниже верны?** 

{% include quiz.html 
  id="3.1"
  type="multiple" 
  question=" " 
  options="$ a \in A$|
$ b \in A$|
$ \\{a\\} \in A$|
$ \\{b\\} \in A$"
answer="1|4" 
%}

{% include quiz.html 
  id="3.2"
  type="multiple" 
  question=" " 
  options="
$ \\{a\\} \subseteq A$|
$ \\{b\\} \subseteq A$|
$ \\{ \\{b\\} \\} \subseteq A$|
$ \\{a, b, c\\} \subseteq A$" 
answer="1|3" 
%}

# Упражнениe 4
{% include quiz.html 
  id="4"
  type="multiple" 
  question="**Какие из утверждений ниже верны?**" 
  options="$\varnothing \in \\{ \varnothing \\}$|
$\varnothing \in \\{ \\{ \varnothing \\} \\}$|
$\varnothing \subseteq \\{ \varnothing \\}$|
$\varnothing \subseteq \\{ \\{ \varnothing \\} \\}$|
$\varnothing \subseteq \varnothing$|
$\varnothing \in \varnothing$" 
answer="1|3|4|5" 
%}

# Упражнениe 5

**Пусть $X = \\{a, b\\}$, $Y = \\{b, c\\}$, $Z = \\{a, b, c, d\\}$  тогда какие из утверждений ниже верны?** 

{% include quiz.html 
  id="5.1"
  type="multiple" 
  question=" " 
  options="$X  \subseteq Y$|
$Y\subseteq X$|
$X \cap Y = Z$|
$X \cap Y \subseteq Z$|
$X \cup Y \subseteq Z$"
answer="4|5" 
%}

{% include quiz.html 
  id="5.2"
  type="multiple" 
  question=" " 
  options="$ Z \setminus  X = \\{ c, d\\}$|
$ Z \setminus  (X \cup Y) =  \\{d\\} $|
$ Z \setminus (X \cap Y) =  \\{a, b, d\\}$|
$ X \setminus Y =  \\{ a \\}$|
$ X \setminus Y = a $"
answer="1|2|4" 
%}