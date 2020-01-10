<p style="color:red; font-family:arial; font-weight:800; text-align:center; font-size:1em; "><a href="https://canadakaknado.info">CANADAKAKNADO.INFO</a><br>база знаний телеграм-чата <a href="https://t.me/canadakaknado">@canadakaknado</a><br>об иммиграции в Канаду</p>

# __CIC PR TableHelper__

Расширение для браузера Chorme [CIC PR TableHelper](https://chrome.google.com/webstore/detail/cic-pr-tablehelper/bibbcbmdkcmmgpodmahndpfakjfiefnn), созданное [@vzakhar](https://t.me/vzakhar), выполняет следующие функции: 

1. Добавляет во все таблицы в профиле Express Entry кнопки ⬆️⬇️ (up / down) для перемещения строк в таблицах вверх и вниз. Новые кнопки располагаются справа от кнопки "Delete Row". 
<p style="text-align: center;"> <img src="https://canadakaknado.info/assets/images/chrome-ext-2.png" width=450> </p>


2. Позволяет загружать в профиль Express Entry тревел хистори из файла в csv-формате. Кнопка загрузки появляется рядом с другими кнопками под таблицей. 
<p style="text-align: center;"> <img src="https://canadakaknado.info/assets/images/chrome-ext-1.png" width=450> </p>

Расширение не изменяет и не удаляет уже заполенные строки таблицы, только добавляет новые. В таблице тревел хистори может содержаться только 50 строк (это ограничение сайта IRCC), так что если вы заполнили уже все строки таблицы при добавлении .csv файла ничего не произойдет; если вы заполнили не всю таблицу, а только, к примеру, 25 строк, то при добавлении .csv файла под этими строками появятся еще 25 - с информацией из первых 25 строк из .csv файла. Таким образом, чтобы заполнить таблицу с помощью .csv файла корректно, нужно заполнять ее с нуля (то есть пустую). Если в вашем .csv файле 50 строк или менее, они полностью перенесутся в таблицу. Если строк больше 50, в таблицу они не поместятся. При истории путешествий, насчитывающей более 50 поездок, оставшие путешествия обычно добавляются в Letter of Explanation с объяснением, что они не поместились в таблицу тревел хистори. 



2) Upload .csv file for travel history.
This one is a little bit tricky. Please note, at the moment it works only with Travel History form. It adds rows to the table up to 50 rows, it does not replace them. For example, if you have 25 rows already in your table the extension will upload only 25 first rows from your .csv file. If you want to fill the from scratch with this extension delete all the rows. 

Here is an example of how to export data from “Google Calc” to a .csv file and then use it with my extension:

Create a “Google Calc” doc and compile your travel history there. Please use the following sequence of columns:

Please make sure that you do not have any things like column headings or anything except data that needs to be sent to the form.
I would also like to highlight some constraints on input data:
Country - should exactly match the name of the country from the “Select Country” drop-down list which is on the travel history page.
DateFrom - should be in format DD.MM.YYYY exactly, with zeroes. For example, “01.02.1999” (without quotes).
DateTo - same as DateFrom.
Cities - nothing special here.
Purpose - use a sequence of whitespace-separated words. Comas or any other punctuation marks do not work here.
In “Google Calc” select File -> Download -> .CSV File and save to some location on your PC.
Open travel history form. Click “Choose .csv file” and chose the file you have downloaded on step 2.
Check all the rows in the table that have been uploaded. If you spelled country names incorrectly, it will show “PROBLEM HERE” instead of a country name. You can edit this row and choose a country manually.
Click the “Save and Exit” button. If there were some other errors, the website will show the number of rows with problems. You can also edit them manually and after that click on the “Save and Exit” button again.
