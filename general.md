## Заголовки

Для создания заголовка используется знак (#) перед символами. Количество знаков (#) увеличивает размер заголовка.

Альтернативный синтаксис для определения заголовка - cимволы необходимо добавить после заголовка.

(=) - heading level 1 

(--) - heading level 2 (Минимальное количество дефисов = 2)


#### Heading Best Practices

Для обратной совместимости с различными реализациями markdown:
 - после знака решетки и перед первым символом заголовка должен быть пробел;
 - Строка до заголовка и после должна быть пустой.


## Параграфы

Для создания параграфа, используется пустая строка между текстом.

#### Paragraph Best Practices

Не использовать пробельные символы перед текстом параграфа. Это может вызвать нежелательное форматирование.

Исключение - если параграф находится в списке.


## Перенос строки

Для переноса строки, после текста необходимо добавить 2 пробела (один tab) и нажать Enter.

#### Line Break Best Practices

 - Использовать html аналог <br>
 - Не использовать альтернативный синтаксис (бэкслэш в конце строки) т.к. он поддерживает малым количеством MD приложений.
 - Некоторые MD приложения создают перенос строки автоматически после нажатия клавиши Enter - не рекомендуется использовать из-за проблем с совместимостью.

## Emphasis

Bold
To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

Bold Best Practices
Markdown applications don’t agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to bold the middle of a word for emphasis.

Italic
To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

Italic Best Practices
Markdown applications don’t agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to italicize the middle of a word for emphasis.


```
vim /etc/ntp.conf
```
```
pwd
```
  ls
#### how to ls
  ls
