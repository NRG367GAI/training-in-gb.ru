# training-in-gb.ru
Educational project
# Инструкция для работы с Markdown

 ## Выделение текста

*Курсив обрамляют (\* или _ ) с двух сторон,* _еще курсив_

**Полужирный текст обрамляют (\*\* или __ ) с дву сторон,** __например так__

Текст может быть одновременно и полу жирным и курсивным для этого текст обрамляют _**например**_

 ## Списки
### Ненумерованные списки (\"*" или "+" Элемент 1)
* Элемент 1
* Элемент 2
+ "Элемент 3

### Нумерованные списки, просто нумируются:
1. Элемент 1
2. Элемент 2

 ## Работа с изображениями

Добавим изображение формула: \!\[текст если изображение не загрузится](имя изображения), изображение должно быть в папке с файлом
![это ПО которое я поставил для работы с git](2022-07-22_210719.jpg)

 ## Ссылки
    В квадратнвх скобках указвыаетсятекст отоброжаймый в документе, а в круглых скобках указывается ссылка которая не отоброжается [ТЕКСТ](ССЫЛКА):
[ссылка на сайт, где больше ньюансов по Markdown](https://daringfireball.net/projects/markdown/syntax)

 ## Работа с таблицами
    Таблицы Markdown физически представлены с помощью тире - для разделения строки заголовка из содержимого и трубы | для столбцов.

Column | Column |
------ | ------ |
Cell   | Cell   |  

Markdown игнорирует интервал. Та же таблица может быть написана следующим образом:

    Letter|Digit|Character
    ---|---|---
    a|4|$
    |365|(
    b| |^  

результат:

Letter|Digit|Character
 ---|---|---
a|4|$
|365|(
b| |^  

Выровнять содержимое таблицы просто для это нужно добавить несколько двоеточий таким образом:

Выравнивание столбца:

: используется для выравнивания столбца. Выравнивание по левому краю - это стандарт.

Column | Column | Column
:----- | :----: | -----:
Left   | Center | Right
align  | align  | align

Труба в содержимом ячейки
Если вы хотите использовать символ канала ( | ) в содержимом ячейки, вам нужно будет избежать его с помощью обратной косой черты.

    Column | Column
    ------ | ------
    \| Cell \|| \| Cell \|  
Это приводит к следующей таблице:

Column | Column
------ | ------
\| Cell \|| \| Cell \| 


 ## Цитаты
 Для цитирования используется ">", достаточно одного такого символаЖ

>«Единственный человек, с которым вы должны сравнивать себя, – это вы в прошлом. И единственный человек, лучше которого вы должны быть, – это вы сейчас». Зигмунд Фрейд

Цитаты могут быть вложены друг в друга (например, цитата в цитате), добавляя дополнительные уровни >:

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

    > This is the first level of quoting.
    >
    > > This is nested blockquote.
    >
    > Back to the first level.

Цитаты могут содержать другие элементы Markdown, включая заголовки, списки и блоки кода:

    > ## This is a header.
    > 
    > 1.   This is the first list item.
    > 2.   This is the second list item.
    > 
    > Here's some example code:
    > 
    >     return shell_exec("echo $input | $markdown_script");

    > ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");


 ## Заключение
 Одновременно мощный и простой, можно сказать язык разметки, позволяющий сделать документ высокого качества. Проще в использовании чем HTML.
