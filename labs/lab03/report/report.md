---
## Front matter
title: "Лабораторная работа 3"
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

  -  Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

   - Выполнить отчёт 3 и 2 лабораторной работы в Markdown

# Выполнение лабораторной работы

Редактируем предоставленный шаблон из /home/rsismailov/work/study/2022-2023/Операционные системы/os-intro/labs/lab03

(рис. @fig:001).

![Папка с отчётом](image/1.jpg){#fig:001 width=70%}

Для создания полного отчёта требуется выделить цель работы, задание, выводы и вставить картинки с выполнением работы.

(рис. @fig:002).

![Цель, Задание, Картинки](image/2.jpg){#fig:002 width=70%}


Для того, чтобы добавить картинки в отчёт, нужно поместить их в папку image. 

(рис. @fig:003).

![папка](image/3.jpg){#fig:003 width=70%}

Выполненный отчёт нужно скомпилировать с помощью терминала

(рис. @fig:004).

![компиляция отчёта](image/4.jpg){#fig:004 width=70%}

Далее стоит проверить отчёт на наличие ошибок во время компиляции

(рис. @fig:005).

![Проверка отчёта](image/5.jpg){#fig:005 width=70%}

# Выводы

Я успешно смог подготовить отчет в markdown второй и третьей лабораторной работы.

