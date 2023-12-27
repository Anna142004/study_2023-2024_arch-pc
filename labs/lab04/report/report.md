---
## Front matter
title: "отчёт по лабораторной работе 4"
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

Освоение процедуры компиляции и сборки программ, написанных на ассемблере NASM


# Выполнение лабораторной работы

1. С помощью утилиты cd перемещаюсь в каталог в котором буду работать.
![](image/01.png){ #fig:001 width=70%, height=70% }
Затем с помощью утилиты touch создаю пустой текстовый файл hello.asm,открываю его и заполняю(вставляю программу для вывода «Hello word!»)
![](image/02.png){ #fig:001 width=70%, height=70% }
Потом я превращаю текст программы в код с помощью транслятора NASM и проверяю правильность выполнения команды с помощью ls.  
![](image/03.png){ #fig:001 width=70%, height=70% }
Следующим шагом было скомпилировать файл hello.asm в файл obj.o и проверка с помощью ls.
![](image/04.png){ #fig:001 width=70%, height=70% }
Затем передаю обьектный файл hello.o на обработку компоновщику LD , чтобы получить исполняемый файл hello и выполняю команду для получения файла main. Запускаю на выполнение созданный файл исполняемый файл hello.
![](image/05.png){ #fig:001 width=70%, height=70% }
# Выполнение заданий для самостоятельной работы.

С помощью утилиты cp создаю копию файла hello.asm с именем lab4.asm .
![](image/06.png){ #fig:001 width=70%, height=70% }
С помощью текстового редактора открываю файл и вношу изменения в программу так , чтоб она выводила мои имя и фамилию.
![](image/07.png){ #fig:001 width=70%, height=70% }
Компилирую текст программы в обьектный файл  и проверяю ,что файл создан. Затем запускаю исполняемый файл  lab4 .
![](image/08.png){ #fig:001 width=70%, height=70% }
Удаляю лишние файлы в текущем каталоге
![](image/09.png){ #fig:001 width=70%, height=70% }
Добавляю файлы на Gitxub.
![](image/10.png){ #fig:001 width=70%, height=70% }

# Выводы

При выполнении данной лабораторной работы я освоила процедуры компиляции и сборки программ, написанных на ассемблере NASM.

