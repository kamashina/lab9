---
## Front matter
lang: ru-RU
title: Лабораторная работа 9
author: |
  М Шариф Камран НПИбд 02-21
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
date: 19 May, 2022

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

# Цель и задачи

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

## Задачи

- Написать текст в файл
- Отредактировать текст
- Использовать окна
- Попробовать поиск

# Выполнение работы
запуск


## Написание текста

- Открыть Emacs
<img width="333" alt="image" src="https://user-images.githubusercontent.com/103488170/169654356-e422208e-b830-4ccf-be3d-ab997e873b5b.png">

- Открыть файл: `C-x C-f`
<img width="624" alt="image" src="https://user-images.githubusercontent.com/103488170/169654371-fb59be77-5dc1-4844-90d7-9834e4e0cc11.png">

- Написать текст
<img width="206" alt="image" src="https://user-images.githubusercontent.com/103488170/169654373-2b3fa5bc-a66f-40fa-9134-7397a668bb0c.png">

- Сохранить файл: `C-x C-s`
<img width="338" alt="image" src="https://user-images.githubusercontent.com/103488170/169654384-800e42e0-85a7-46fd-b37a-dc9c54a60e16.png">

## Редактирование текста

- Вырезать строку до конца: `C-k`
<img width="241" alt="image" src="https://user-images.githubusercontent.com/103488170/169654394-49cea5da-12f0-4532-9861-48ba3d767fc6.png">

- Вставить: `C-y`
<img width="259" alt="image" src="https://user-images.githubusercontent.com/103488170/169654405-838497cf-104c-4ed6-837a-d46bf5c897cf.png">

- Выделить текст: `C-space`
нет
- Скопировать в *kill-буфер*: `M-w`

- Отменить действие: `C-/`

Переместить курсор:

- в начало строки: `C-a`
<img width="130" alt="image" src="https://user-images.githubusercontent.com/103488170/169654424-e69a4824-d7f3-486e-a22b-f91afcd744c5.png">

- в конец строки: `C-e`
<img width="346" alt="image" src="https://user-images.githubusercontent.com/103488170/169654434-3b6f66d8-d7ca-4ae6-8195-4bac2cfdca34.png">

- в начало буфера: `M-<`

- в конец буфера: `M->`

## Окна

Разделить окна: `C-x 2` и `C-x 3`

Закрыть окна: `C-x 0`


# Заключение

Emacs -- это редактор с широкими возможностями для расширения, что делает его очень настраиваемым.
Благодаря широкому набору возможностей его можно считать одним из первых IDE.

Как и VI, редактор имеет много различных возможностей, но их сложно использовать в полную силу, и требуется потратить время на изучение.
В этой работе мы познакомились с самым базовым функционалом.
