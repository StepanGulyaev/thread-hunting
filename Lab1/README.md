# Лабораторная работа №1
Гуляев Степан

## Цель работы

Получить сведения об используемой системе

## Исходные данные

1.  MacBook Pro 15 Retina late 2013
2.  ОС Gentoo Linux x86_64

## План работы

1.  Получить информацию о дистрибутиве
2.  Получить информацию о ядре
3.  Получить информацию о процессоре

## Ход работы

1.Получим информацию о дистрибутиве

``` bash
stepan@DodoBird ~ $ lsb_release -a
LSB Version:  n/a
Distributor ID:  Gentoo
Description:  Gentoo Linux
Release:  2.13
Codename:  n/a
```

В результате выполнения данной команды было определён используемый
дистрибутив - Gentoo.

2.Получим информацию о ядре

``` bash
stepan@DodoBird ~ $ uname -srm
Linux 6.1.19-gentoo x86_64
```

В результате выполнения данной команды была получена версия ядра - Linux
6.1.19-gentoo x86_64.

3.Получим информацию о процессоре

``` bash
stepan@DodoBird ~ $ cat /proc/cpuinfo | grep "model name"
model name  : Intel(R) Core(TM) i7-4750HQ CPU @ 2.00GHz
```

Используемый процессор - Intel(R) Core(TM) i5-10600K с тактовой частотой
2.00GHz.

## Оценка результата

В результате лабораторной работы мы получили информацию об используемой
системе.

## Вывод

Используя команды Linux, мы получили сведения о системе.