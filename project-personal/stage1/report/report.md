
# **Отчёт по первому этапу проекта**
discipline: Основы информационной безопасности
group: НПМбд-02-21
author: Газизова Регина Ильгамовна

---
## Front matter
title: "Отчёт по первому этапу проекта"
subtitle: "Основы информационной безопасности"
author: "Газизова Регина"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

## Цель работы

Установить дистрибутив Kali Linux в виртуальную машину


## Выполнение лабораторной работы

1. Скачиваем архив с kali linux с офицального сайта и распаковываем его (рис.1)

<img src="D:\Изображения\16.png"  width="600"> (рис.1)

2. Устанавливаем в virtualbox и запускаем (рис.2)

<img src="D:\Изображения\17.png"  width="600"> (рис.2)

3. После запуска вводим логин и пароль (должно было быть root toor, но в моем случае было kali kali) (рис.3)

<img src="D:\Изображения\14.png"  width="600"> (рис.3)

4. Наблюдаем рабочий стол запущенного дистрибутива kali linux(рис.5)

<img src="D:\Изображения\15.png"  width="650"> (рис.4)


# Выводы

Установили дистрибутив Kali Linux в виртуальную машину
