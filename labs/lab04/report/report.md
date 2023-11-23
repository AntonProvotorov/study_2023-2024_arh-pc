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

## Выполнение заданий для самостоятельной работы.

С помощью утилиты cp создаю в текущем каталоге копию файла hello.asm с именем lab5.asm (рис. [-@fig:010]).

![Создание копии файла](image/.png){ #fig:010 width=70% }

С помощью текстового редактора mousepad открываю файл lab4.asm и вношу изменения в программу так, чтобы она выводила мои имя и фамилию. (рис. [-@fig:011]).

![Изменение программы](image/.png){ #fig:011 width=70% }

Компилирую текст программы в объектный файл (рис. [-@fig:012]). Проверяю с помощью утилиты ls, что файл lab5.o создан.

![Компиляция текста программы](image/.png){ #fig:012 width=70% }

Передаю объектный файл lab4.o на обработку компоновщику LD, чтобы получить исполняемый файл lab5 (рис. [-@fig:013]).

![Передача объектного файла на обработку компоновщику](image/.png){ #fig:013 width=70% }

Запускаю исполняемый файл lab4, на экран действительно выводятся мои имя и фамилия (рис. [-@fig:014]).

![Запуск исполняемого файла](image/14.png){ #fig:014 width=70% }



![Создании копии файлов в новом каталоге](image/15.png){ #fig:015 width=70% }

Удаляю лишние файлы в текущем каталоге с помощью утилиты rm, ведь копии файлов остались в другой директории (рис. [-@fig:016]).

![Удаление лишних файлов в текущем каталоге](image/16.png){ #fig:016 width=70% }

С помощью команд git add . и git commit добавляю файлы на GitHub, комментируя действие как добавление файлов для лабораторной работы №5 (рис. [-@fig:017]).

![Добавление файлов на GitHub](image/17.png){ #fig:017 width=70% }

Отправляю файлы на сервер с помощью команды git push (рис. [-@fig:018]).

![Отправка файлов](image/18.png){ #fig:018 width=70% }



# Выводы

При выполнении данной лабораторной работы я освоил процедуры компиляции и сборки программ, написанных на ассемблере NASM.



