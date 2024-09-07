---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 3"
author: "Гафоров Нурмухаммад Вомикович"

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

Сделать сайт на конструкторе Hugo [@github]

# Задание

Добавить информацию о навыках (Skills).  
Добавить информацию об опыте (Experience).  
Добавить информацию о достижениях (Accomplishments).  
Сделать пост по прошедшей неделе.  
Добавить пост на тему по выбору  

# Выполнение лабораторной работы

Укажем уже в известном нам индекс файле свои скиллы и хобби (рис. [-@fig:001]).

![Скиллы и хобби](image/1.jpg){#fig:001}

Добавим пост о LaTeX (рис. [-@fig:002]).

![Пост о ЛаТеХ](image/2.jpg){#fig:002}

И пост о прошедшей неделе (рис. [-@fig:003]).

![Пост о прошедшей неделе](image/3.jpg){#fig:003}

Изменённый нами раздел сайта теперь выглядит так (рис. [-@fig:004]).

![Изменённый раздел сайта](image/4.jpg){#fig:004}

# Выводы

В результате работы были написаны посты, а также добавленны скиллы и хобби

# Список литературы{.unnumbered}

::: {#refs}
:::
