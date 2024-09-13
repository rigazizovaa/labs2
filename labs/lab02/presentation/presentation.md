---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №2
subtitle: Основы информационной безопасности
author:
  - Газизова Р.И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 13 сентября 2024

## i18n babel
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

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---


# Процесс выполнения

### Создаем учетную запись гостя (имя пользователя и пароль)

<img src="D:\Изображения\1.png"  width="600">

### Входим как пользователь guest

<img src="D:\Изображения\2.png"  width="600">

### Определяем директорию, в которой находимся. Уточняем имя пользователя, его группу, а также группы, куда входит пользователь.

<img src="D:\Изображения\3.png"  width="600">

### Находим свою учётную запись и определяем uid(1001) и git(1001) пользователя

<img src="D:\Изображения\4.png"  width="650">

<img src="D:\Изображения\5.png"  width="600">

### Определяем существующие в системе директории и их права

<img src="D:\Изображения\6.png"  width="600">

###  Пытаемся проверить, какие расширенные атрибуты установлены на поддиректориях, находящихся в директории /home

<img src="D:\Изображения\7.png"  width="600">

### Создаем в домашней директории поддиректорию dirr1. Определяем командами, какие права доступа и расширенные атрибуты были выставлены на директорию dirr1

<img src="D:\Изображения\8.png"  width="600">

### Снимаем с директории dirr1 все атрибуты 

<img src="D:\Изображения\9.png"  width="600">

### Попытались создать в директории dirr1 файл file1. 

<img src="D:\Изображения\10.png"  width="600">