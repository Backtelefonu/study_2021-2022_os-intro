---
## Front matter
lang: ru-RU
title: Лабораторная работа №6
author: |
    Кузнецов Василий Юрьевич - студент группы НФИбд-02-21
date: 30.04.2022

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

# Поиск файлов. Перенаправление ввода-вывода. Просмотр запущенных процессов

## Цель работы

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.

## Выполнение лабораторной работы

1. Запишите в файл file.txt названия файлов, содержащихся в каталоге /etc. Допишите в этот же файл названия файлов, содержащихся в вашем домашнем каталоге 

![](../report/images/1.png)

## 

2. Выведите имена всех файлов из file.txt, имеющих расширение .conf, после чего
запишите их в новый текстовой файл conf.txt.

![](../report/images/2.png)

## 

3. Определите, какие файлы в вашем домашнем каталоге имеют имена, начинавшиеся с символа c? Предложите несколько вариантов, как это сделать.

![](../report/images/3.png)

## 

4. Выведите на экран (по странично) имена файлов из каталога /etc, начинающиеся с символа h.

![](../report/images/4.png)

## 

5. Запустите в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log.

![](../report/images/5.png)

## 

6. Удалите файл ~/logfile. Запустите из консоли в фоновом режиме редактор gedit.

![](../report/images/6.png)

## 

7. Определите идентификатор процесса gedit, используя команду ps, конвейер и фильтр
grep. Как ещё можно определить идентификатор процесса? Прочтите справку (man) команды kill, после чего используйте её для завершения
процесса gedit.

![](../report/images/7.png)

## 

8. Выполните команды df и du, предварительно получив более подробную информацию
об этих командах, с помощью команды man.

![](../report/images/8.png)

## 

9. Воспользовавшись справкой команды find, выведите имена всех директорий, имеющихся в вашем домашнем каталоге.

![](../report/images/9.png)

## Вывод

Ознакомились с инструментами поиска файлов и фильтрации текстовых данных.
Приобрели практические навыки по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.
