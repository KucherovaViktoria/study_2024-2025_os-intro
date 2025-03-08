---
## Front matter
lang: ru-RU
title: Лабораторная работа №1
subtitle: Установка и конфигурация операционной системы на виртуальную машину
author:
  - Кучерова В. В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 06 марта 2025

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Кучерова Виктория Васильевна
  * Студентка 1-го курса, НММбд-02-24
  * Российский университет дружбы народов
  * [1132246778@pfur.ru](mailto:1132246778@pfur.ru)

:::
::: {.column width="30%"}


:::
::::::::::::::

# Вводная часть

## Актуальность

Умение создавать Linux-окружение необходимо для широкого круга задач, включая разработку программного обеспечения, администрирование серверов, тестирование, научные исследования и создание документации.

## Объект и предмет исследования

- Процесс установки и настройки операционной системы Linux на виртуальной машине Virtualbox.
- Этапы установки, настройки и установка необходимого программного обеспечения для создания рабочей среды.

## Цели и задачи

- Установка Linux на Virtualbox.
- Установка инструментов Markdown и TeXlive.

## Материалы и методы

- Установка ОС: Использование графического установщика Linux в Virtualbox.
- Настройка ОС: командная строка и редактирование конфигов для автообновления, отключение SELinux, настройка клавиатурыи т.д.
- Установка ПО: Менеджер пакетов для установки Markdown и TeXlive.

# Выполнение лабораторной работы

## Создание виртуальной машины

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

Создадим новую виртуальную машину

![Создание виртуальной машины](image/1.jpg){#fig:001 width=70%}

:::
::: {.column width="50%"}

:::
::::::::::::::


## Обновления

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

Обновим все пакеты

![Обновление пакетов](image/2.jpg){#fig:002 width=90%}

:::
::: {.column width="30%"}

:::
::::::::::::::


## Отключение SELinux

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

Отключим SELinux

![SELinux](image/3.jpg){#fig:003 width=70%}

:::
::: {.column width="50%"}

![SELinux](image/4.jpg){#fig:004 width=110%}

:::
::::::::::::::

## Настройка раскладки клавиатуры

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

Отредактируем конфигурационный файл /etc/X11/xorg.conf.d/00-keyboard.conf

![Настройка раскладки клавиатуры](image/5.jpg){#fig:005 width=90%}

:::
::: {.column width="30%"}

:::
::::::::::::::


## Работа с языком разметки Markdown

Установим pandoc и pandoc-crossref 

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![pandoc](image/6.jpg){#fig:006 width=90%}

:::
::: {.column width="50%"}

![pandoc-crossref](image/7.jpg){#fig:007 width=90%}

:::
::::::::::::::

## texlive

Установим дистрибутив TeXlive

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

![TeXlive](image/8.jpg){#fig:008 width=90%}

:::
::: {.column width="30%"}

:::
::::::::::::::


# Результаты

## Выводы

- Успешно установлена и настроена Linux на Virtualbox.
- Приобретены навыки установки ОС, базовой настройки и установки ПО.



