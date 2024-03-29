Комментарии к классу "Статья конференции СПИСОК"
================================================

Класс  сам  по  себе  содержит  большое  количество  установок:  язык,
кодировка, параметры страницы, оформление заголовков и подзаголовков и
т.д. В  файле со статьёй,  таким образом, дополнительных  установок не
требуется.

При  вёрстке  для унификации  внешнего  вида  статьи с  внешним  видом
статей,  свёрстанных  при  помощи  MS  Word  и  LibreOffice/OpenOffice
Writer, используется шрифт Times New Roman.

Чистовая вёрстка выполняется при помощи системы XeLaTeX.

У PDFLaTeX есть объективные проблемы  при работе с кириллицей и Times,
поэтому при  сборке с помощью  PDFLaTeX используются гарнитуры  TeX по
умолчанию --  семейство Computer  Modern. При этом  изменяются внешний
вид текста, а так же, из-за отличия  в метриках, его объём в строках и
страницах.  PDFLaTeX  для черновых  работ  использовать  можно, но  не
рекомендуется.

При работе  с XeLaTeX  класс spisok-article  использует джентльменский
набор  Times  New Roman,  Arial  и  Courier  New. Шрифты  должны  быть
установлены в системе. В Windows  они доступны всегда, в Unix-подобные
системы легко инсталлируются.

XeLaTeX есть в современных версиях дистрибутивов MikTeX TeXLive.

Для  сборки макета  статьи  необходимо дважды  (для корректной  работы
перекрёстных ссылок и списка литературы) выполнить команду:

    xelatex имя_файла.tex

При   подаче   чистовой   версии  материалов   просьба   предоставлять
программному  комитету архив,  содержащий исходные  файлы, необходимые
для сборки макета и получившийся PDF.

Автор шаблона:

Луцив Дмитрий Вадимович
dluciv@math.spbu.ru
dluciv@dluciv.name


Большое спасибо!
