---
## Front matter
title: "Отчёт по лабораторной работе №7"
subtitle: "Операционные системы"
author: "Морозова Мария Вячеславовна"

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

Ознакомление с файловой системой Линукс, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами.

# Задание

Выполнить примеры, создать директории, создать и переместить файлы, присвоить права доступа.


# Выполнение лабораторной работы

Копируем и проверяем что находится в equipment  (рис. [-@fig:001]).

![Содержимое](image/1.png){#fig:001 width=70%}


Создаём директорию и файлы в ней. (рис. [-@fig:002]).

![Работа с ski plases](image/2.png){#fig:002 width=70%}


Создаём директории и присваиваем им необходимые права доступа (рис. [-@fig:003]).

![Работа с chmod и mkdir](image/3.png){#fig:003 width=70%}


Копируем, перемещаем файлы, изменяем права доступа (рис. [-@fig:004]).

![Работа с cp, mv chmod](image/4.png){#fig:004 width=70%}

# Выводы

После выполнения работы были приобретены навыки практические навыки по применению команд для работы с файлами и каталогами.

