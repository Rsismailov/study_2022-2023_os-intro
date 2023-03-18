---
## Front matter
title: "Отчёт о выполнении. Индивидуальный проект. Этап 2"
author: "Руслан Исмаилов Шухратович"

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

Целью данной работы является создание собственного сайта

# Задание

Доработать сайт и добавить пост


# Выполнение лабораторной работы

Редактируем /home/rsismailov/Hugo/content/authors/_index.md, для того, чтобы поменять на нашем сайте описание автора. 

(рис. @fig:001).

![индекс](image/1.jpg){#fig:001 width=70%}

Вот как будут выглядеть внесенные изменения на нашем сайте. 

(рис. @fig:002).

![](image/2.jpg){#fig:002 width=70%} 

Добавим фотографию, заменив файл avatar.png

(рис. @fig:003).

![](image/3.jpg){#fig:003 width=70%}

Добавим пост на тему управление версиями. Git.

для этого отредактируем один из существующих постов

(рис. @fig:004).

![](image/4.jpg){#fig:004 width=70%}

Вот как выглядят изменения 

(рис. @fig:005).

![](image/5.jpg){#fig:005 width=70%}


# Выводы

Я смог Доработать сайт и добавить пост
