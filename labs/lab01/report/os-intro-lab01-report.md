# Лабораторная работа №4
Савенкова Татьяна Александровна

-   [<span class="toc-section-number">1</span> Цель
    работы](#цель-работы)
-   [<span class="toc-section-number">2</span> Задание](#задание)
-   [<span class="toc-section-number">3</span> Теоретическое
    введение](#теоретическое-введение)
-   [<span class="toc-section-number">4</span> Выполнение лабораторной
    работы](#выполнение-лабораторной-работы)
-   [<span class="toc-section-number">5</span> Домашнее
    задание](#домашнее-задание)
-   [<span class="toc-section-number">6</span> Выводы](#выводы)
-   [Список литературы](#список-литературы)

# Цель работы

Целью данной работы является приобретение практических навыков установки
операционной системы на виртуальную машину, настройки минимально
необходимых для дальнейшей работы сервисов.

# Задание

-   Установка Linux на Qemu
-   Установка необходимого ПО
-   Первоначальная настройка ОС для дальнейшей работы

# Теоретическое введение

QEMU — свободная программа с открытым исходным кодом для эмуляции
аппаратного обеспечения различных платформ. Включает в себя эмуляцию
процессоров Intel x86 и устройств ввода-вывода. Может эмулировать 80386,
80486, Pentium, Pentium Pro, AMD64 и другие x86- совместимые процессоры;
ARM, MIPS, RISC-V, PowerPC, SPARC, SPARC64 и частично m68k. Работает на
Syllable, FreeBSD, OpenBSD, FreeDOS, Linux, Windows 9x, Windows 2000,
Mac OS X, QNX\[8\]\[9\]\[10\], Android и др.

# Выполнение лабораторной работы

Захожу в виртуальную машину и создаю операционную систему
(<a href="#fig-001" class="quarto-xref">рис. 1</a>)

<img src="image/1.png" style="width:70.0%" />

Настраиваю память (<a href="#fig-002" class="quarto-xref">рис. 2</a>)

<img src="image/2.png" style="width:70.0%" />

Устанавливаю Fedora Linux 43 Sway
(<a href="#fig-003" class="quarto-xref">рис. 3</a>)

<img src="image/3.png" style="width:70.0%" />

После установки скачиваю набор необходимых пакетов для работы с ОС.
(<a href="#fig-004" class="quarto-xref">рис. 4</a>)

<img src="image/4.png" style="width:70.0%" />

Запускаю скрипт для автоматического обновления пакетов через пакетный
менеджер dnf. (<a href="#fig-005" class="quarto-xref">рис. 5</a>)

<img src="image/5.png" style="width:70.0%" />

Отключаю защиту SELinux, так как на данном курсе мы не будем
рассматривать работу с ней.
(<a href="#fig-006" class="quarto-xref">рис. 6</a>)

<img src="image/6.png" style="width:70.0%" />

Настраиваю xkb, добавляю вторую раскладку клавиатуры с русским языком и
задаю переключение на right ctrl.
(<a href="#fig-007" class="quarto-xref">рис. 7</a>)

<img src="image/7.png" style="width:70.0%" />

Проверяю корректность заданного имени для hostname.
(<a href="#fig-008" class="quarto-xref">рис. 8</a>)

<img src="image/8.png" style="width:70.0%" />

Устанавливаю pandoc, pandoc-crossref, texlive для работы над отчетами
для лабораторных работ.
(<a href="#fig-009" class="quarto-xref">рис. 9</a>)

<img src="image/9.png" style="width:70.0%" />

# Домашнее задание

Проверяю последовательность загрузки графического окружения командой
dmesg | grep -i с указанием вывода желаемого нахождения
(<a href="#fig-010" class="quarto-xref">рис. 10</a>)

<img src="image/10.png" style="width:70.0%" />

<img src="image/11.png" style="width:70.0%" />

<img src="image/12.png" style="width:70.0%" />

<img src="image/13.png" style="width:70.0%" />

<img src="image/14.png" style="width:70.0%" />

<img src="image/15.png" style="width:70.0%" />

<img src="image/16.png" style="width:70.0%" />

# Выводы

В ходе выполнения лабораторный работы прибрела навыки установки
виртуальной машины на Qemu, установила ряд пакетов и настроила ОС для
дальнейшей работы на ней.

# Список литературы
