---
## Front matter
lang: ru-RU
title:  Основы информационной безопасности. Индивидуальный проект
subtitle: Этап № 4. Использование Nikto
author: |
	Демидова Е.А.
institute: Российский Университет дружбы народов
date: 09.09.2023

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
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Демидова Екатерина Алексеевна
  * студентка группы НКНбд-01-21
  * Российский университет дружбы народов
  * <https://github.com/eademidova>

:::
::: {.column width="30%"}

![](./image/ava.jpg)

:::
::::::::::::::

# Вводная часть

## Цели и задачи

**Целью** данной работы является является использование Nikto для сканирования уязвимостей веб-приложения.

**Задачи:**

- Проанализировать уязвимости веб-приложения DVWA с помощью сканера Nikto.

**Инструмент:** DVWA, Nikto

# Выполнение лабораторной работы

## Установка

![Проверка установки ПО](image/1.png){#fig:001 width=70%}

## Сканирование и анализ

![Проверка уязвимостей по доменному имени](image/2.png){#fig:002 width=70%}

## Сканирование и анализ

![Отчет об уязвимостях в формате html](image/3.png){#fig:003 width=70%}

## Сканирование и анализ

![Проверка уязвимостей с указанием порта](image/4.png){#fig:004 width=70%}

# Заключение

## Выводы

В результате выполнения работы был использован сканер Nikto для сканирования уязвимостей веб-приложения.

## Список литературы

1. DVWA [Электронный ресурс]. GitHub, Inc, 2024. URL: https://github.com/digininja/DVWA.
2. Обзор сканера Nikto для поиска уязвимостей в веб-серверах [Электронный ресурс]. 2006–2024, Habr, 2023. URL: https://habr.com/ru/companies/first/articles/731696/.
