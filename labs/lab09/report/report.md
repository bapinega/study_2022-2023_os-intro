---
## Front matter
title: "Лабораторная работа №9"
subtitle: "Операционные системы"
author: "Пинега Белла Александровна"

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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Задание

1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором emacs.
3. Выполнить упражнения.
4. Ответить на контрольные вопросы.

# Теоретическое введение

Emacs представляет собой мощный экранный редактор текста, написанный на языке
высокого уровня Elisp.

# Выполнение лабораторной работы
1. Открою emacs.
![рис.1](image/1.png){#fig:001 width=70%}
2. Создам файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f (C-x C-f).
![рис.2](image/2.png){#fig:002 width=70%}
3. Наберу текст
![рис.3](image/3.png){#fig:003 width=70%}
4. Сохраню файл с помощью комбинации Ctrl-x Ctrl-s (C-x C-s). Вырежу одной командой целую строку (С-k).
![рис.4](image/4.png){#fig:004 width=70%}
5.2. Вставлю эту строку в конец файла (C-y).
![рис.5](image/5.png){#fig:005 width=70%}
5.3. Выделю область текста (C-space).
![рис.6](image/7.png){#fig:007 width=70%}
5.4. Скопирую область в буфер обмена (M-w). Вставлю область в конец файла.
![рис.7](image/8.png){#fig:008 width=70%}
5.6. Вновь выделю эту область и на этот раз вырежу её (C-w).
![рис.8](image/9.png){#fig:009 width=70%}
![рис.9](image/10.png){#fig:010 width=70%}
5.7. Отменю последнее действие (C-/).
![рис.10](image/11.png){#fig:011 width=70%}
6.1. Перемещу курсор в начало строки (C-a).
![рис.11](image/12.png){#fig:012 width=70%}
6.2. Перемещу курсор в конец строки (C-e).
![рис.12](image/13.png){#fig:013 width=70%}
6.3. Перемещу курсор в начало буфера (M-<).
![рис.13](image/14.png){#fig:014 width=70%}
6.4. Перемещу курсор в конец буфера (M->).
![рис.14](image/15.png){#fig:015 width=70%}
7.1. Выведу список активных буферов на экран (C-x C-b).
![рис.15](image/16.png){#fig:016 width=70%}
7.2. Закрою это окно (C-x 0).
![рис.16](image/17.png){#fig:017 width=70%}
8.1. Поделю фрейм на 4 части: 
![рис.17](image/18.png){#fig:018 width=70%}
8.2. В каждом из четырёх созданных окон открою новый буфер (файл) и введу
несколько строк текста.
![рис.18](image/19.png){#fig:019 width=70%}
9.1. Переключусь в режим поиска (C-s) и найду несколько слов, присутствующих
в тексте.
![рис.19](image/21.png){#fig:021 width=70%}
9.2. Переключаюсь между результатами поиска, нажимая C-s.
![рис.20](image/22.png){#fig:022 width=70%}
![рис.21](image/23.png){#fig:023 width=70%}
9.3. Выйду из режима поиска, нажав C-g.
![рис.22](image/24.png){#fig:024 width=70%}
9.4. Перейду в режим поиска и замены (M-%)
![рис.23](image/26.png){#fig:026 width=70%}
9.5. Испробую другой режим поиска, нажав M-s o
![рис.24](image/28.png){#fig:028 width=70%}
Разница в том что при поиске указывает номера строк в которых введенное слово выделяется цветом.

# Выводы

Я познакомилась с операционной системой Linux. Получила практические навыки работы с редактором Emacs.

# Список литературы{.unnumbered}

::: {#refs}
:::
