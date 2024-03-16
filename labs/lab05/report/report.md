---
## Front matter
title: "Лабораторная работа №5"
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

Изучить менеджер паролей pass; 
Изучить установку ежедневного программного обеспечения.

# Задание

Установить менеджер паролей pass;
Установить дополнительное программное обеспечение;
Создать собственный репозиторий с помощью утилит;

# Выполнение лабораторной работы

Устанавливаю менеджер паролей pass с помощью соответствующей команды (рис.[-@fig:001]):

![Установка менеджера паролей](image/1.jpg){#fig:001 width=70% height=70%}

Затем устанавливаю gopass (рис.[-@fig:002]):

![Установка менеджера gopass](image/2.jpg){#fig:002 width=70% height=70%}

Инициализируем хранилище (рис.[-@fig:003]):

![Инициализация хранилища](image/3.jpg){#fig:003 width=70% height=70%}

Создаю структуру git (рис.[-@fig:004]):

![Создание структуры git](image/4.jpg){#fig:004 width=70% height=70%}

Задаю адрес репозитория на хостинге (рис.[-@fig:005]):

![Задаю адрес репозитория](image/5.jpg){#fig:005 width=70% height=70%}

Меняю название ветки (рис.[-@fig:006]):

![Изменение названия](image/6.jpg){#fig:006 width=70% height=70%}

Делаю прямые изменения в файловой системе. Коммичу вручную и выкладываю изменения (рис.[-@fig:007]):

![Изменения в файловой системе](image/7.jpg){#fig:007 width=70% height=70%}

Устанавливаю плагин browserpass (рис.[-@fig:008]):

![Установка](image/8.jpg){#fig:008 width=70% height=70%}

Устанавливаю плагин browserpass(продолжение) (рис.[-@fig:009]):

![Установка плагина](image/9.jpg){#fig:009 width=70% height=70%}

Создаю файл для пароля (рис.[-@fig:010]):

![Создание файла](image/10.jpg){#fig:010 width=70% height=70%}

С помощью соответствующей команды система генерирует пароль (рис.[-@fig:011]):

![Пароль](image/11.jpg){#fig:011 width=70% height=70%}

Устанавливаю дополнительное программное обеспечение (рис.[-@fig:012]):

![Установка дополнительного программного обеспечения](image/12.jpg){#fig:012 width=70% height=70%}

Устанавливаю шрифты (рис.[-@fig:013]):

![Установка шрифтов](image/13.jpg){#fig:013 width=70% height=70%}

Устанавливаю шрифты(продолжение) (рис.[-@fig:014]):

![Установка шрифтов](image/14.jpg){#fig:014 width=70% height=70%}

Устанавливаю шрифты(продолжение) (рис.[-@fig:015]):

![Продолжение установки шрифтов](image/15.jpg){#fig:015 width=70% height=70%}

Устанавливаю бинарный файл. Скрипт определяет архитектуру процессора и операционную систему и скачивает необходимый файл (рис.[-@fig:016]):

![Установка бинарного файла](image/16.jpg){#fig:016 width=70% height=70%}

Создаю свой репозиторий для конфигурационных файлов на основе шаблона (рис.[-@fig:017]):

![Создание репозитория](image/17.jpg){#fig:017 width=70% height=70%}

Инициализирую chezmoi с репозиторием dotfiles (рис.[-@fig:018]):

![Инициализация chezmoi](image/18.jpg){#fig:018 width=70% height=70%}

Перехожу во вторую виртуальную машину. Также инициализирую chezmoi с репозиторием dotfiles (рис.[-@fig:019]):

![Инициализация chezmoi на другой машине](image/19.jpg){#fig:019 width=70% height=70%}

Устанавливаю свои dotfiles на новый компьютер с помощью одной команды (рис.[-@fig:020]):

![Установка dotfiles](image/20.jpg){#fig:020 width=70% height=70%}

Проверяю, какие изменения внесёт chezmoi в домашний каталог (рис.[-@fig:021]):

![Проверка изменений](image/21.jpg){#fig:021 width=70% height=70%}

Соглашаюсь с изменениями (рис.[-@fig:022]):

![Соглашаюсь с изменениями](image/22.jpg){#fig:022 width=70% height=70%}

Можно извлечь изменения из репозитория и применить их одной командой (рис.[-@fig:023]):

![Соглашаюсь с изменениями](image/23.jpg){#fig:023 width=70%, height=70%}

Извлекаю последние изменения из своего репозитория (рис.[-@fig:024]):

![Извлечение изменений](image/24.jpg){#fig:024 width=70% height=70%}

Применяю изменения, так как доволен изменениями (рис.[-@fig:025]):

![Применяю изменения](image/25.jpg){#fig:025 width=70% height=70%}

Можно автоматически фиксировать и отправлять изменения в исходный каталог в репозиторий.
Эта функция отключена по умолчанию (рис.[-@fig:026]):

Чтобы включить её, добавьте в файл конфигурации ~/.config/chezmoi/chezmoi.toml следующее:

git:
    autoCommit = true
    autoPush = true
    
Захожу в файл для редактирования.

![Команда для редактирования файла](image/26.png){#fig:026 width=70% height=70%}

Вижу что никаких изменений вносить не нужно (рис.[-@fig:027]):

![Файл](image/27.jpg){#fig:027 width=70% height=70%}

# Выводы

При выполнении данной лабораторной работы я получил практические навыки
 в настройке рабочей среды.
# Список литературы{.unnumbered}

::: {#refs}
:::
