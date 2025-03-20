---
## Front matter
title: "Индивидуальный проект."
subtitle: "Этап 1"
author: "Талебу тенке франк устон"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

установить дистрибутив Kali Linux в виртуальную машину

# Выполнение лабораторной работы

1. Скачал с сайта дистрибутив kali
2.  Добавил образ в Virtual box
3.  Запустил и начал установку 
4.  В общем, прошел классические настройки

Убедимся, что имя в терминале соответствует имени, выданному в компьютерном классе

[-@fig:001]).
[-@fig:002]).
[-@fig:003]).
[-@fig:004]).
[-@fig:005]).
[-@fig:006]).
[-@fig:007]).
[-@fig:009]).

![Название рисунка](image/1.jpg){#fig:001 width=70%}
![Название рисунка](image/2.jpg){#fig:002 width=70%}
![Название рисунка](image/3.jpg){#fig:003 width=70%}
![Название рисунка](image/4.jpg){#fig:004 width=70%}
![Название рисунка](image/5.jpg){#fig:005 width=70%}
![Название рисунка](image/6.jpg){#fig:005 width=70%}
![Название рисунка](image/7.jpg){#fig:005 width=70%}
![Название рисунка](image/8.jpg){#fig:005 width=70%}

# Выводы

установить дистрибутив Kali Linux в виртуальную машину.

# Список литературы{.unnumbered}

::: {#refs}
:::
