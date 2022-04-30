---
## Front matter
lang: ru-RU
title: Отчёт по первому этапу ИП
author: |
	Газизова Регина
institute: |
	РУДН, Москва, Россия
date: 29 апреля 2022

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

## Цель работы

Разместить на Github pages заготовки для персонального сайта.

# Ход лабораторной работы

## Скачиваем шаблон темы сайта и переносим его в наш репозиторий

![Копирование шаблона в наш репозиторий](image/2.png){ #fig:001 width=70% }

## Размещаем его на хостинге git.

![Размещение на хостинге](image/1.png){ #fig:002 width=70% }

## Устанавливаем параметр для URLs сайта. 

![URLs сайта](image/3.png){ #fig:003 width=70% }

![Меняем URLs сайта](image/4.png){ #fig:004 width=70% }
	
## Создаём пустой репозиторий с именем rigazizovaa.github.io 
	
![Репозиторий на github](image/5.png){ #fig:005 width=70% }
	
## Клонируем созданный репозиторий
	
![Копирование репозитория](image/6.png){ #fig:006 width=70% }

## Переходим на главную ветку репозитория и создаём пустой файл README.md 

![Создание файла](image/7.png){ #fig:007 width=70% }

## Перекидываем файл в репозиторий на github
	
![Перенос файла на github](image/8.png){ #fig:008 width=70% }

## Меняем адрес сайта в файле config.yaml, вызывая редактирование файла в консоле	
	
![Вызов файла config.yaml](image/9.png){ #fig:009 width=70% }
	
![Вызов файла config.yaml](image/10.png){ #fig:010 width=70% }
		
##  Создаём каталог publiс и привязываем к нему репозиторий rigazizovaa.github.io
### Репозиторий не привязывается т.к. public игнорируется 

![Привязка репозитория](image/11.png){ #fig:011 width=70% }

##  Создаём каталог publiс и привязываем к нему репозиторий rigazizovaa.github.io
### В файле каталога Site делаем так, что бы каталог public не игнорировался
	
![Убераем игнорирование](image/12.png){ #fig:012 width=40% }

##  Создаём каталог publiс и привязываем к нему репозиторий rigazizovaa.github.io
### Снова привязываем репозиторий и нам это удаётся

![Привязываем репозиторий](image/13.png){ #fig:013 width=70% }

## Вызываем hugo, чтобы скомпелировать файлы

![Вызов hugo](image/14.png){ #fig:014 width=70% }

## Загружаем всё на github

![Загрузка на github](image/15.png){ #fig:015 width=70% }

## Загружаем всё на github
		
![Загрузка на github](image/16.png){ #fig:016 width=80% }	
 
## Проверяем выгрузку файлов на github

![Репозиторий](image/17.png){ #fig:017 width=70% }
 
## Итоговый сайт

![Сайт](image/18.png){ #fig:018 width=70% }


## Вывод: 
Научились использовать шаблоны сайта с github и размещать на Github pages заготовки для персонального сайта.



