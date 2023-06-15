# Титульный лист

РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ

Факультет физико-математических и естественных наук









**Лабораторная работа 10**

По дисциплине "Операционные системы"













Выполнил:

Студент группы НПВбм-01-19

Студенческий билет №: 1032193844 

Саидов Ахият Магомадович

Руководитель: Валиева Татьяна Рефатовна























Москва 2023



# Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs

# Начало работы

1. Откроем _emacs_.

   ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%811.JPG?raw=true)

   _Рисунок 1_

2. Создадим файл _lab07.sh_ с помощью комбинации _Ctrl-x Ctrl-f_.

   ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%812.JPG?raw=true)

   _Рисунок 2_

3. Наберем текст:

   ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%813.JPG?raw=true)

   _Рисунок 3_

4. Сохраним файл с помощью комбинации _Ctrl-x Ctrl-s_.

5. Проделаем с текстом стандартные процедуры редактирования, каждое действие должно осуществляться комбинацией клавиш:

   * Вырезать одной командой целую строку _(Сtrl-k)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%814.JPG?raw=true)

     _Рисунок 4

   * Вставить эту строку в конец файла _(Ctrl-y)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%815.JPG?raw=true)

     _Рисунок 5_

   * Выделить область текста _(Ctrl-space)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%816.JPG?raw=true)

     _Рисунок 6_

   * Скопировать область в буфер обмена _(Alt-w)_.

   * Вставить область в конец файла _(Ctrl-y)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%817.JPG?raw=true)

     _Рисунок 7_

   * Вновь выделить эту область и на этот раз вырезать её _(Ctrl-w)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%818.JPG?raw=true)

     _Рисунок 8_

   * Отмените последнее действие _(Ctrl-/)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%819.JPG?raw=true)

     _Рисунок 9_

6. Научимся использовать команды по перемещению курсора:

   * Переместите курсор в начало строки _(Ctrl-a)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8110.JPG?raw=true)

     _Рисунок 10_

   * Переместите курсор в конец строки _(Ctrl-e)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8111.JPG?raw=true)

     _Рисунок 11_

   * Переместите курсор в начало буфера _(Alt-<)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8112.JPG?raw=true)

     _Рисунок 12_

   * Переместите курсор в конец буфера _(Alt->)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8113.JPG?raw=true)

     _Рисунок 13_

7. Управление буферами

   * Вывести список активных буферов на экран _(Ctrl-x Ctrl-b)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8114.JPG?raw=true)

     _Рисунок 14_

   * Переместитесь во вновь открытое окно _(Ctrl-x  0)_ со списком открытых буферов и переключитесь на другой буфер.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8115.JPG?raw=true)

     _Рисунок 15_

   * Закройте это окно _(Ctrl-x 0)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8116.JPG?raw=true)

     _Рисунок 16_

   * Теперь вновь переключайтесь между буферами, но уже без вывода их списка на экран _(Ctrl-x b)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8117.JPG?raw=true)

     _Рисунок 17_

8. Управление окнами:

   * Поделите фрейм на 4 части: разделите фрейм на два окна по вертикали _(Ctrl-x 3)_, а затем каждое из этих окон на две части по горизонтали _(Ctrl-x 2)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8118.JPG?raw=true)

     _Рисунок 18_

   * В каждом из четырёх созданных окон откройте новый буфер (файл) и введите несколько строк текста.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8119.JPG?raw=true)

     _Рисунок 19_

9. Режим поиска:

   * Переключитесь в режим поиска _(Ctrl-s)_ и найдите несколько слов, присутствующих в тексте.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8120.JPG?raw=true)

     _Рисунок 20_

   * Переключайтесь между результатами поиска, нажимая _(Ctrl-s)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8121.JPG?raw=true)

     _Рисунок 21_

   * Выйдите из режима поиска, нажав _(Ctrl-g)_.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8122.JPG?raw=true)

     _Рисунок 22_

   * Перейдите в режим поиска и замены _(Alt + shift - %)_, введите текст, который следует найти и заменить, нажмите _Enter_ , затем введите текст для замены. После того как будут подсвечены результаты поиска, нажмите _!_ для подтверждения замены.

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8123.JPG?raw=true)

     _Рисунок 23_

   * Испробуйте другой режим поиска, нажав _(Alt-s o)_. Объясните, чем он отличается от обычного режима?

     ![](https://github.com/Akhiyat/Laboratory-work/blob/main/Lab10/screencast/%D0%A0%D0%B8%D1%8124.JPG?raw=true)

     _Рисунок 24_

# Вывод

Мы познакомились с операционной системой Linux. Получили практические навыки работы с редактором Emacs

# Контрольные вопросы

1. Emacs представляет собой мощный экранный редактор текста, написанный на языке высокого уровня Elisp.
2. Отличаются комбинации команд от общепринятых часто-используемых.
3. Отдельное место хранения определенного текста.
4. Да, в _emacs_ можно открыть больше 10 окон.
5. По умолчанию при открытии _emacs_ создает два буфера - _scratch_ и _messages_.
6. _Ctrl + C > |_ и _Ctrl + C > Ctrl + |_.
7. Ctrl + x > 3 или 2.
8. _.emacs_.
9. Навигационная клавиша _"влево"_.
10. Редактор _vi_ мне показался удобнее, т.к. в нем имеется интерфейс для пользователя, большая часть команд имеется на экране, а значит не требуется их запоминать.
