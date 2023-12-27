---
## Front matter
title: "Отчет по лабороторной работе 3"
subtitle: "Архитектура компьютера"
author: "Тарасова Анна"

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
Целью работы является освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown

# Выполнение лабораторной работы
1. Первым делом я скачала Texlive и pandoc ,а также pandoc-crossref.
![](image/01.png){ #fig:001 width=70%, height=70% }
![](image/02.png){ #fig:001 width=70%, height=70% }
2. Обновляю локальный репозиторий, скачав изменения из удаленного репозитория с помощью команды git pull.
![](image/03.png){ #fig:001 width=70%, height=70% }
3. Затем я перехожу в каталог с шаблоном отчета, компилирую его и открываю сгенерированный файл report.docx
![](image/04.png){ #fig:001 width=70%, height=70% }
А также открываю сгенерированный файл report.pdf
![](image/05.png){ #fig:001 width=70%, height=70% }
Удаляю полученные файлы с помощью make clean и с помощью команды ls проверяю, удалились ли созданные файлы.
![](image/06.png){ #fig:001 width=70%, height=70% }
Открываю файл report.md и начинаю заполнять отчет.
![](image/07.png){ #fig:001 width=70%, height=70% }
Компилирую файл с отчетом и загружаю его на Github.


# Выводы

В результате выполнения данной лабороторной работы я освоила процедуры оформления отчетов с помощью легковесного языка Markdown

