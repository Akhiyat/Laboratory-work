# Титульный лист

РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ

Факультет физико-математических и естественных наук









**Лабораторная работа 5**

По дисциплине "Операционные системы"













Выполнил:

Студент группы НПВбм-01-19

Студенческий билет №: 1032193844 

Саидов Ахият Магомадович

Руководитель: Валиева Татьяна Рефатовна























Москва 2023



# Цель работы

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# Начало работы

1) Определим полное имя нашего домашнего каталога.

<img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%811.JPG?raw=true" style="zoom:80%;" />

_Рисунок 1_

2) Выполним следующие действие:

   * Перейдем в каталог _/tmp_

     <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%812.JPG?raw=true" style="zoom:80%;" /> 

     _Рисунок 2_

   * Выведем на экран содержимое каталога  _/tmp_. Для этого используем команду `ls`с различными опциями.

     <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%813.JPG?raw=true" style="zoom: 33%;" />	 <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%814.JPG?raw=true" style="zoom: 33%;" />

     _Рисунок 3_												_Рисунок 4_

     <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%815.JPG?raw=true" style="zoom:33%;" />	 <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%816.JPG?raw=true" style="zoom:33%;" />

     _Рисунок 5_												_Рисунок 6_

     <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%817.JPG?raw=true" style="zoom:33%;" />	 <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%818.JPG?raw=true" style="zoom:33%;" />

     _Рисунок 7_ 												_Рисунок 8_

     * `ls -a` - вывод список файлов [требуется для вывода скрытых файлов, имена которых начинаюься с точки].

     * `ls -l` - вывод список файлов в длинном формате. 

       Формат: _режим доступа > количество ссылок > имена владельца > размер в байтах > время последних изменений > имя файла._

   * Определим, есть ли в каталоге _/var/spool_ подкаталог с именем _cron_.

     <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%819.JPG?raw=true" style="zoom: 80%;" />

     _Рисунок 9_

   * Перейдем в домашний каталог и выведем на экран его содержимое.

     <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8110.JPG?raw=true" style="zoom: 80%;" />

     _Рисунок 10_

3) Выполним следующие действия: 

   * В домашнем каталоге создадим новый каталог с именем _newdir_

     <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8111.JPG?raw=true" style="zoom:80%;" />

     _Рисунок 11_

   * В каталоге _/newdir`_ создадим новый каталог с именем _morefun_

     <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8112.JPG?raw=true" style="zoom:80%;" />

     _Рисунок 12_ 

   * В домашнем каталоге создадим одной командой три новых каталога с именем _letters, memos, misk_.

     Затем удалим эти каталоги одной командой.

     <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8113.JPG?raw=true" style="zoom:80%;" />

     _Рисунок 13_

   * Попробуем удалить ранее созданный каталог _newdir_ командой `rm`.

     <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8114.JPG?raw=true" style="zoom:80%;" />

     _Рисунок 14_

   * Удалим каталог _/newdir/morefun из домашнего каталога.

     <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8115.JPG?raw=true" style="zoom:80%;" />

     _Рисунок 15_

     Каталог /newdir ранее был удален вместе со всеми подкаталогами, поэтому мы не можем удалить несуществующий файл.

4) С помощью команды `man`, определим какую опцию команды `ls` нужно использовать для просмотра содержимое не только указанного каталога, но и подкаталогов, входящих в него

   Используем команду `man ls`.

   <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8116.JPG?raw=true" style="zoom:80%;" />

   _Рисунок 16_

   Находим необходимую опцию.

   <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8117.JPG?raw=true" style="zoom:80%;" />

   _Рисунок 17_

5) С помощью команды `man`, определим набор опций команды `ls`, позволяющие отсортировать по времени последнего изменения выводимый список содержимого каталогов с развернутым описанием файлов.

   <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8118.JPG?raw=true" style="zoom:80%;" />

   _Рисунок 18_

6) Используя команду `man` для просмотра описания следующих: `cd, pdw, mkdir, rmdir, rm`

   <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8119.JPG?raw=true" style="zoom:80%;" />

   _Рисунок 19_

   * `man cd` - отображение текущего диска и каталога.

   <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8120.JPG?raw=true" style="zoom:80%;" />

   _Рисунок 20_

   * `man pdw` - отображение рабочего каталога, вывод пути.

   <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8121.JPG?raw=true" style="zoom:80%;" />

   _Рисунок 21_

   * `man mkdir` - создание каталога

   <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8122.JPG?raw=true" style="zoom:80%;" />

   _Рисунок 22_

   * `man rmdir` - удаление каталога

   <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8123.JPG?raw=true" style="zoom:80%;" />

   _Рисунок 23_

   * `man rm` - удалить файл

   <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8124.JPG?raw=true" style="zoom:80%;" />

   _Рисунок 24_

7. Используя информацию, полученную при помощи команды history, выполним модификацию и исполнение нескольких команд из буфера команд.

   <img src="https://github.com/Akhiyat/Laboratory-work/blob/main/Lab05/creencast/%D0%A0%D0%B8%D1%8125.JPG?raw=true" style="zoom:80%;" />

   _Рисунок 25_

   # Вывод

   Мы приобрели практических навыки взаимодействия пользователя с системой посредством командной строки.

   # Контрольные вопросы

   1. Командная строка - программа, которая служит промежуточным слоем между человеком и машиной и передаёт друг другу команды и ответы машине и человеку соотвественно.
   2. Используется команда pwd - print working directory.
   3. При помощи команды ls (-опции) / tree(-опции)
   4. Скрытые файлы - файлы, которые нежелательны для просмотра, редактирования и перемещения имют впереди названия точку, чтобы вести имна скрытых файлов используют ls -a.
   5. Команда rm для удаления файла, для удаления папки rmdir.
   6. Используя команду history. ?) Используя команду history, запомнить номер команды, потом написать ошибку и её замену.
   7. Для таких случаев используется символ ;
   8. Символ экранирования нужен для того, чтобы командная строка не приняла специальные символы ., *, … за команду.
   9. ls -l показывает дополнительную информацию о файле - дата изменения, права доступа,список владельцев.
   10. Относительный путь- путь к файлу, к которому не нужно задавать полное местонахождение, а можно обойтись быстым вводом - text.txt, при этом файла и терминала должны быть открыто из одного каталога или указать путь order/text.txt
   11. Команда help 13 Вводим первые буквы, нажимаем клавишу Tab.
