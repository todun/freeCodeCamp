---
title: Extract Matches
localeTitle: Экстракционные матчи
---
## Экстракционные матчи

Используя метод `match()` , вы можете извлекать части строки, которые соответствуют вашему регулярному выражению. В этой задаче вы извлекаете слово «кодирование» из предоставленной строки.

## Подсказка 1:

Измените ваше регулярное выражение, чтобы определить слово «кодирование».

## Подсказка 2:

Вы вызвали метод `match()` в строке?

## Оповещение о спойлере - решение впереди!

## Решение:

```javascript
let extractStr = "Extract the word 'coding' from this string."; 
 let codingRegex = /coding/; 
 let result = extractStr.match(codingRegex); 

```