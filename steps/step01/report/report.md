---
## Front matter
title: "Отчет проект"
subtitle: "Шаг 1"
author: "Мазуркевич Анастасия Дмитриевна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Создание сайта научного работника

# Задание

Размещение заготовки на Github pages



# Выполнение лабораторной работы

Заходим на репозиторий с шаблоном

![Заходим на репозиторий с шаблоном](image/1.jpg){#fig:001 width=70%}

Создаем репозиторий по шаблону

![Создаем репозиторий по шаблону](image/3.jpg){#fig:002 width=70%}

Открываем шаблон в github pages

![Открываем шаблон в github pages](image/4.jpg){#fig:003 width=70%}

Настраиваем github pages

![настраиваем](image/5.jpg){#fig:004 width=70%}

Публикуем сайт

![создаем сайт](image/6.jpg){#fig:005 width=70%}

Сайт опубликован

![сайт создан](image/7.jpg){#fig:006 width=70%}

Заходим на сайт и проверяем, всё верно

![открываем сайт и проверяем](image/8.jpg){#fig:007 width=70%}

# Выводы

Разместили заготовки на Github pages
# Список литературы{.unnumbered}

::: {#refs}
:::
