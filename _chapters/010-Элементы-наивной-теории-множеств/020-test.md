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
  question="Какие из утверждений верны?" 
  options="$\\{a, b \\} = \\{b, a\\}$|
  $\\{a, b, b, b, b, c \\} = \\{b, a, c\\}$"
  answer="1|2" 
%}

# Упражнениe 2

{% include quiz.html 
  id="2" 
  type="multiple" 
  question="Пусть $A = \\{a, \\{b\\}, c \\}$.  Какие из утверждений верны?" 
  options="$ a \in A$|
$ b \in A$|
$ \\{a\\} \in A$|
$ \\{b\\} \in A$|
$ \\{a\\} \subseteq A$|
$ \\{b\\} \subseteq A$|
$ \\{ \\{b\\} \\} \subseteq A$|
$ \\{a, b, c\\} \subseteq A$" 
answer="1|4|5|7" 
%}

# Упражнениe 3
{% include quiz.html 
  id="3" 
  type="multiple" 
  question="Какие из утверждений верны?" 
  options="$\varnothing \in \\{ \varnothing \\}$|
$\varnothing \in \\{ \\{ \varnothing \\} \\}$|
$\varnothing \subseteq \\{ \varnothing \\}$|
$\varnothing \subseteq \\{ \\{ \varnothing \\} \\}$|
$\varnothing \subseteq \varnothing$|
$\varnothing \in \varnothing$" 
answer="1|3|4|5" 
%}

