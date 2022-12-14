**РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ**

презентация **по лабораторной работе № [12]{.ul}**

*[дисциплина: Операционные системы]{.ul}*

Студент группы [НПИбд-01-21]{.ul}

Студенческий билет № [1032205621]{.ul}

[Фамилия Имя Отчествo Дессие Абди Бедаса]{.ul}

**МОСКВА**

20[22]{.ul}г.

Цель работы:

Изучить основы программирования в оболочке ОС UNIX. Научиться писать
более сложные командные файлы с использованием логических управляющих
конструкций и циклов.

Ход работы:

-   Осуществили вход в систему, создали текстовый документ, затем
    > перешли в него. Написали командный файл, реализующий упрощённый
    > механизм семафоров. Командный файл в течение некоторого времени t1
    > дожидается освобождения ресурса, выдавая об этом сообщение, а
    > дождавшись его освобождения, использует его в течение некоторого
    > времени t2\<\>t1, также выдавая информацию о том, что ресурс
    > используется соответствующим командным файлом (процессом).
    > Запустили командный файл в одном виртуальном терминале в фоновом
    > режиме, перенаправив его вывод в другой, в котором также запущен
    > этот файл, но не фоновом, а в привилегированном режиме. Доработали
    > программу так, чтобы имелась возможность взаимодействия трёх и
    > более процессов.

```{=html}
<!-- -->
```
-   Реализовали команду man с помощью командного файла. Изучили
    > содержимое каталога /usr/share/man/man1. В нем находятся архивы
    > текстовых файлов, содержащих справку по большинству установленных
    > в системе программ и команд. Каждый архив можно открыть командой
    > less сразу же просмотрев содержимое справки. Командный файл должен
    > получать в виде аргумента командной строки название команды и в
    > виде результата выдавать справку об этой команде или сообщение об
    > отсутствии справки, если соответствующего файла нет в каталоге
    > man1.

```{=html}
<!-- -->
```
-   Используя встроенную переменную \$RANDOM, напиали командный файл,
    > генерирующий случайную последовательность букв латинского
    > алфавита. Учли, что \$RANDOM выдаёт псевдослучайные числа в
    > диапазоне от 0 до 32767.

Вывод:

Мы изучили основы программирования в оболочке ОС UNIX, а также научилиь
писать более сложные командные файлы с использованием логических
управляющих конструкций и циклов.
