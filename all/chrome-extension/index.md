<p style="color:red; font-family:arial; font-weight:800; text-align:center; font-size:1em; "><a href="https://canadakaknado.info">CANADAKAKNADO.INFO</a><br>база знаний телеграм-чата <a href="https://t.me/canadakaknado">@canadakaknado</a><br>об иммиграции в Канаду</p>

# __CIC PR TableHelper__

Расширение для браузера Chorme [CIC PR TableHelper](https://chrome.google.com/webstore/detail/cic-pr-tablehelper/bibbcbmdkcmmgpodmahndpfakjfiefnn), созданное [@vzakhar](https://t.me/vzakhar), выполняет следующие функции: 

1. Добавляет во все таблицы в профиле Express Entry кнопки ⬆️⬇️ (up / down) для перемещения строк в таблицах вверх и вниз. Новые кнопки располагаются справа от кнопки "Delete Row". 
<p style="text-align: center;"> <img src="https://canadakaknado.info/assets/images/chrome-ext-2.png" width="450"> </p>

2. Позволяет загружать в профиль Express Entry тревел хистори из файла в csv-формате. Кнопка загрузки появляется рядом с другими кнопками под таблицей. 
<p style="text-align: center;"> <img src="https://canadakaknado.info/assets/images/chrome-ext-1.png" width="450"> </p>

Расширение не изменяет и не удаляет уже заполенные строки таблицы, только добавляет новые. 

В таблице тревел хистори может содержаться только 50 строк (это ограничение сайта IRCC), так что, если вы уже заполнили все строки таблицы, при добавлении .csv файла ничего не произойдет; если вы заполнили не всю таблицу, а только, к примеру, 25 строк, то при добавлении .csv файла под этими строками появятся еще 25 - с информацией из первых 25 строк из .csv файла. Таким образом, чтобы заполнить таблицу с помощью .csv файла корректно, нужно заполнять ее с нуля, удалив все существующие строки. 

Если в вашем .csv файле 50 строк или менее, они полностью перенесутся в таблицу. Если строк больше 50, в таблицу они не поместятся. При истории путешествий, насчитывающей более 50 поездок, оставшие путешествия обычно добавляются в Letter of Explanation с объяснением, что они не поместились в таблицу тревел хистори. 

Если вы не знаете, что такое формат csv, ниже приведен пример создания такого файла с помощью Гугл Таблиц (Google Sheets). Аналогично файл в этом формате можно создать практически в любом редакторе таблиц. 

1. Создаем пустую [Гугл Таблицу](https://docs.google.com/spreadsheets). 

2. Заполняем ее данными следующим образом:
Ячейка А - страна; написание страны должно полностью совпадать с ее написанием в выпадающем меню в соответствующей ячейке таблицы тревел хистори в вашем профиле.
Ячейка В - дата приезда в формате DD.MM.YYYY; в случае если день или месяц - однозначные числа, в начале необходимо добавить ноль, например, *01.02.2019*, а не *1.2.2019*.
Ячейка С - дата отъезда в формате DD.MM.YYYY; в случае если день или месяц - однозначные числа, в начале необходимо добавить ноль, например, *03.04.2019*, а не *3.4.2019*.
Ячейка D - город(а) или другие населенные пункты, которые вы посещали в этой стране, через пробел (запятые и другие знаки препинания использовать не нужно).
Ячейка Е - цель визита; если цель состоит из нескольких слов, так же разделите их пробелами (запятые и другие знаки препинания использовать не нужно).

<p style="text-align: center;"> <img src="https://canadakaknado.info/assets/images/my-travel-history.jpg"> </p>

Помните, что никакой другой информации в таблице содержаться не должно: ни других ячеек, ни других строк (например, названий колонок). 

3. Далее файл необходимо скачать, выбрав формат csv. 

<p style="text-align: center;"> <img src="https://canadakaknado.info/assets/images/travel-history-download.jpg"> </p>





Check all the rows in the table that have been uploaded. If you spelled country names incorrectly, it will show “PROBLEM HERE” instead of a country name. You can edit this row and choose a country manually.
Click the “Save and Exit” button. If there were some other errors, the website will show the number of rows with problems. You can also edit them manually and after that click on the “Save and Exit” button again.
