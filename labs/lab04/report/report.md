---
## Front matter
title: "Отчёт по лабораторной работе №4"
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

Получение навыков правильной работы с репозиториями git.

# Задание

Выполнить работу для тестового репозитория.
Преобразовать рабочий репозиторий в репозиторий с git-flow  и conventional commits.

# Теоретическое введение

Gitflow workflow опубликована и популяризована Винсентом Дриссеном
Gitflow workflow предполагает выстраивание строгой модели ветвления с учётом выпуска проекта.

# Выполнение лабораторной работы

Установка git-flow из коллекции репозиториев corp.  (рис. [-@fig:001]).

![Установка](image/1.png){#fig:001 width=70%}

Установка node.js (рис. [-@fig:002]).

![Установка](image/2.png){#fig:002 width=70%}

Настройка node.js и общепринятых коммитов.(рис. [-@fig:003]).

![Настройка](image/3.png){#fig:003 width=70%}

Создали репозиторий git. (рис. [-@fig:004]).

![Репозиторий](image/4.png){#fig:004 width=70%}

Делаем первый коммит и выкладываем на github.(рис. [-@fig:005]).

![Коммит](image/5.png){#fig:005 width=70%}

Заполнили название и лицензию пакета. (рис. [-@fig:006]).

![Параметры пакета](image/6.png){#fig:006 width=70%}

Выгружаем на github, инициализируем  git-flow. (рис. [-@fig:007]).

![Загрузка,инициализируем  git-flow](image/7.png){#fig:007 width=70%}

Установим префикс для ярлыков в v, проверили на какой мы ветке, загрузили репозиторий в хранилище. (рис. [-@fig:008]).

![Конфигурация git-flow](image/8.png){#fig:008 width=70%}

Создали релиз на github, создадим ветку для новой функциональности, объединяем ветки, создаем релиз 1.2.3(рис. [-@fig:009]).

![Работа с репозиторием](image/9.png){#fig:009 width=70%}

Залили релизную ветку в основную ветку, отправили данные на github. (рис. [-@fig:010]).

![Создание релиза git-flow](image/10.png){#fig:010 width=70%}

Создали на github релиз с комментарием из журнала изменений. (рис. [-@fig:011]).

![Создание релиза git-flow](image/11.png){#fig:011 width=70%}

# Выводы

В процессе выполнения лабораторной работы были получены навыки правильной работы с репозиториями git.


