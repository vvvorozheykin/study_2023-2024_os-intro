---
## Front matter
title: "Лабораторная работа №10"
subtitle: "Отчет"
author: "Ворожейкин Владимир Вячеславович"

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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Задание

Создать новый файл с использованием vi;
Редактировать созданный файл.

# Выполнение лабораторной работы

Создаю каталог для выполнения работы (рис.[-@fig:001]):

 ![Создание каталога](image/1.png){#fig:001 width=70% height=70%}
 
 Перехожу в него (рис.[-@fig:002]):

 ![Переход в каталог](image/2.png){#fig:002 width=70% height=70%}
 
 Вызываю vi и создаю файл hello.sh (рис.[-@fig:003]):

 ![Информация о mc](image/3.png){#fig:003 width=70% height=70%}
 
 Нажимаю клавишу i для ввода текста (рис.[-@fig:004]):

 ![Ввод текста](image/4.png){#fig:004 width=70% height=70%}
 
 Перехожу в командный режим с помощью клавиши Esc (рис.[-@fig:005]):

 ![Командный режим](image/5.png){#fig:005 width=70% height=70%}
 
 Ввожу :wq для сохранения файла (рис.[-@fig:006]):

 ![Сохранение файла](image/6.png){#fig:006 width=70% height=70%}
 
 Делаю файл исполняемым (рис.[-@fig:007]):

 ![Команда для исполняемого файла](image/7.png){#fig:007 width=70% height=70%}

Вызываю vi для редактирования файла (рис.[-@fig:008]):

 ![Вызов vi](image/8.png){#fig:008 width=70% height=70%}
 
 Заменяю на второй строке слово HELL на HELLO (рис.[-@fig:009]):

 ![Замена слова](image/10.png){#fig:009 width=70% height=70%}
 
 В четвертой строке пишу слово local (рис.[-@fig:010]):

 ![Запись слова](image/11.png){#fig:010 width=70% height=70%}
 
 На последней строке файла пишу echo $HELLO (рис.[-@fig:011]):

 ![Запись фразы](image/13.png){#fig:011 width=70% height=70%}
 
 Запускаю файл для проверки работоспособности (рис.[-@fig:012]):

 ![Работа файла](image/14.png){#fig:012 width=70% height=70%}
 
# Выводы

Во время выполнения данной лабораторной работы я приобрел практические навыки в работе с vi и научился редактировать файлы в данном редакторе.

# Список литературы{.unnumbered}

::: {#https://esystem.rudn.ru/pluginfile.php/2288526/mod_resource/content/4/008-lab_vi.pdf}
:::
