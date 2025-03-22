---
## Front matter
title: "Отчёт по индивидуальному проекту. Этап 2" 
subtitle: "Дисциплина: Основы информационной безопасности"
author: "Талебу тенке франк устон НКАбд-04-23 "

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

- Установка DVWA в гостевой системе Kali Linux.

# Выполнение лабораторной работы

- Перейдем в каталог html: cd /var/www/html Клонируем репозиторий git: sudo git clone https://github.com/digininja/DVWA.git. Перейдем к файлу конфигурации в каталоге установки  cd DVWA. затем давайте проверим список на наличие содержимого каталога
- Скопируем файл конфигурации и переименуем его: cp config.inc.php.dist config.inc.php
- Откроем файл настроек vim  config/config.inc.php 
- Установим mariadb 
- Запустим базу данных: sudo su-, затем mysql 

- создадим нового пользователя базы данных. Для этого давайте подключимся к базе данных как пользователь root, а затем воспользуемся следующими командами:
- Запустиv сервер Apache 
- Открываем DVWA в браузере: localhost/DVWA/setup.php 
- Давайте нажмем Create / Reset Database. Давайте нажмем create, чтобы создать базу данных. Затем введите имя пользователя и пароль

(рис. [-@fig:001]):
 (рис. [-@fig:002]). 
 
![Клонируем репозиторий](image/1.png){#fig:001 width=70%}
![конфигурации](image/2.png){#fig:002 width=70%}

(рис. [-@fig:003]).

![редактировать файл ](image/3.png){#fig:003 width=70%}

(рис. [-@fig:004]).

![Установка mariadb ](image/4.png){#fig:004 width=70%}

(рис. [-@fig:005]).

![Запустим базу ](image/5.png){#fig:005 width=70%}
(рис. [-@fig:006]).

![создадим нового пользователя ](image/6.png){#fig:006 width=70%}

(рис. [-@fig:007]): sudo service apache2 start

![Запустим базу ](image/7.png){#fig:007 width=70%}
(рис. [-@fig:008]).

![Запустим базу ](image/8.png){#fig:008 width=70%}

# Выводы

- В ходе выполнения данной лабораторной работыб, я установил DVWA в гостевой системе Kali Linux.

# Список литературы{.unnumbered}

1. Парасрам, Ш. Kali Linux: Тестирование на проникновение и безопасность : Для профессионалов. Kali Linux / Ш. Парасрам, А. Замм, Т. Хериянто, и др. – Санкт-Петербург : Питер, 2022. – 448 сс.

