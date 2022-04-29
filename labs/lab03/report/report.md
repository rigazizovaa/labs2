---
## Front matter
title: "Отчет по 3 лабораторной работе"
subtitle: "По дисциплине Операционные системы"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

- Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.
- Вкачестве отчёта предоставить отчёты в 3 форматах:pdf,docx и md(вархиве,поскольку он должен содержать скриншоты,Makefile ит.д.)

# Теоретическое введение

- Чтобы создать заголовок,используйте знак (#)
- Чтобы задатьдлятекста полужирное начертание,заключите его в двойные звездочки
- Чтобы задатьдлятекста курсивное начертание,заключите его в одинарные звездочки
- Чтобы задать для текста полужирное и курсивное начертание,заключите его в тройные звездочки
- Неупорядоченный (маркированный) список можно отформатировать с помощью звез-дочек илитире
- Упорядоченный список можно отформатировать с помощью соответствующих цифр
# Выполнение лабораторной работы

Настройка GitHub. Изначально создаём учетную запись и заполняем основные данные на официальном сайте. https://github.com. (рис. [-@fig:001])

![1](image/001.png){ #fig:001 width=70% }

Затем синхронизируем учетную запись с компьютером с помощью терминала. (рис. [-@fig:002])

![2](image/002.png){ #fig:002 width=70% }

Начинаем базовую настройку git: настроим utf-8 в выводе сообщений git, верификацию и подписание коммитов git, зададим имя начальной̆ ветки (будем называть её master), параметр autocrlf, параметр safecrlf (рис. [-@fig:003])

![3](image/003.png){ #fig:003 width=70% }

Создадим ключ ssh по алгоритму rsa с ключевым размером 4096 бит и привяжем его к github.(рис. [-@fig:004])

![4](image/004.png){ #fig:004 width=70% }

Создадим ключ pgp. Генерируем ключ и из предложенных опций выбираем опции описанные в условии лабораторной работы. (рис. [-@fig:005]) 

![5](image/005.png){ #fig:005 width=70% }

Добавим PGP ключ в GitHub. Для этого выводим список ключей и скопируем отпечаток приватного ключа. Скопируем наш сгенерированный PGP ключ в буфер обмена. С помощью настроек GitHub (https://github.com/settings/keys),  добавим наш скопированный ключ, вставив его в поле ввода, которое появилось после нажатия кнопки New GPG key (рис. [-@fig:006], [-@fig:007])

![6](image/006.png){ #fig:006 width=70% }

![7](image/007.png){ #fig:007 width=70% }

Настроим автоматических подписей коммитов git(рис. [-@fig:008])

![8](image/008.png){ #fig:008 width=70% }

Создадим новый репозиторий курса на основе шаблона и далее настроим каталог курса, удалив ненужные файлы, создав необходимые каталоги и отправив файлы на сервер (рис. [-@fig:009],[-@fig:010],[-@fig:011])

![9](image/009.png){ #fig:009 width=70% }

![10](image/010.png){ #fig:010 width=70% }

![11](image/011.png){ #fig:011 width=70% }

# Выводы

В данной лабораторной работе я научилась работать с Github (создавать и привязывать учетную запись к компьютеру). Разобрала основные команды git и рассмотрела, как их применять их при работе с Github. Изучила идеологию и научилась применять средства контроля версий


# Список литературы{.unnumbered}

::: {#refs}
:::
