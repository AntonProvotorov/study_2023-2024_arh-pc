---
## Front matter
title: "Отчет по лабораторной работе №4"
author: "Провоторов АНтон Григорьевич"

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
![Создание рабочего каталога и файла в нем, переход в этот каталог и открытие соданного файла](image/11.png){#fig:001 width=70%}
![Ввод текста  воткрывшийся файл](image/22.png){#fig:001 width=70%}
![Компиляция сходного файла hello.asm в объектный код и проверка](image/33.png){#fig:001 width=70%}
![Компиляция исходного файла hello.asm в объектный obj.o, проверка и создание файла листига](image/44.png){#fig:001 width=70%}
![Компоновка объектного файла в исполняемый ( исполняемый файл имеет имя main, а объектный obj.o](image/55){#fig:001 width=70%}
![Компоновка объктного файла и проверка](image/66.png){#fig:001 width=70%}
![Запуск исполняемого файла, все работает без ошибок](image/77){#fig:001 width=70%}



# Выводы




