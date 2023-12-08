---
## Front matter
title: "отчёт по лабораторной работе №3"
subtitle: "Дисциплина: Архитектура компьютера"
author: "Тарасова Анна Викторовна"

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
Целью работы является освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.
# Задание
1. Установка необходимого ПО

2. Заполнение отчета по выполнению лабораторной работы №3 с помощью языка разметки Markdown

3. Задание для самостоятельной работы

# Теоретическое введение
Markdown - легковесный язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций. Внутритекстовые формулы делаются аналогично формулам LaTeX. B Markdown вставить изображение в документ можно с помощью непосредственного указания адреса изображения. Синтаксис Markdown для встроенной ссылки состоит из части [link text], представляющей текст гиперссылки, и части (file-name.md) - URL- адреса или имени файла, на который дается ссылка. Markdown поддерживает как встраивание фрагментов кода в предложение, так и их размещение между предложениями в виде отдельных огражденных блоков. Огражденные блоки кода это простой способ выделить синтаксис для фрагментов кода.

# Выполнение лабораторной работы
1. Установка необходимых программ. /home/vboxuser/Изображения/Снимки экрана/Снимок экрана от 2023-11-26 18-42-25.png /home/vboxuser/Изображения/Снимки экрана/Снимок экрана от 2023-11-26 18-43-07.png
2. Заполнение отчета по выполнению лабороторной работы №3 с помощью языка разметки Markdown.
Открыв терминал перехожу в каталог курса, сформированный при выполнении прошлой лабороторной работы и обновляю локальный репозиторий с помощью команды git pull /home/vboxuser/Изображения/Снимки экрана/Снимок экрана от 2023-11-26 18-46-53.png 
Затем перехожу в каталог с шаблоном отчета по лабороторной работе №3 ,компилирую шаблон с использованием Makefile , с помощью команды make и открываю сгенерированный файл report.docx. /home/vboxuser/Изображения/Снимки экрана/Снимок экрана от 2023-11-26 23-35-28.png. 
Также открываю сгенерированный файл report.pdf /home/vboxuser/Изображения/Снимки экрана/Снимок экрана от 2023-11-26 23-35-58.png
Удаляю файлы с помощью команды make clean и с помощью команды ls проверяю,удалились ли созданные мной файлы. 
file:///home/vboxuser/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BA%D0%B8%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-12-08%2001-28-17.png
Затем я открываю файл report.md и начинаю заполнять отчет с помощью языка разметки Markdown.
file:///home/vboxuser/%D0%98%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BA%D0%B8%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-12-08%2001-34-13.png
# Выводы
В ходе выполнения лабороторной работы №3 я освоила процедуры оформления отчетов с помощью лексического языка разметки Markdown.



