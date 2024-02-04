# 🔒 Cтепень зрелости REST API

## Уровень 0: Собачье болото (The Swamp of POX)

В википедии данный уровень зрелости называется болотом оспы, но мне такое название не очень нравится(звучит противно), поэтому добавим немного поэзии и переведем **The Swamp of Plain Old XML**, как болото Простого Старого Ыксемеля, что сокращенное читается, как ПСЫ, а значит собачье.

Вообще, данный уровень нулевой потому, что систему, данного уровня вообще нельзя классифицировать, как **RESTful**.

В такой реализации у нас есть один **URL**, на который поступают все запросы (обычно **POST**) и система уже по составу запроса решает, что от нее хотят и какой ей дать на это ответ.

Однако, даже для такого спорного уровня зрелости существуют свои правила:

*   **В URL адресах должны использоваться дефисы** **(-)**, чтобы улучшить их читаемость. Это значит, что при составлении адресов должен использоваться spinal-case.

    Пример:

    [http://api.example.com/blogs/guy-levin/posts/this-is-my-first-post](http://api.example.com/blogs/guy-levin/posts/this-is-my-first-post) - хорошо

    [http://api.example.com/blogs/guylevin/posts/thisismyfirstpost](http://api.example.com/blogs/guylevin/posts/thisismyfirstpost) - плохо
*   **Не должны использоваться нижние подчеркивания** **(\_)**

    Тут все очевидно – смотрим правило 1
*   Предпочтительно использовать строчные буквы при составлении URL адресов

    Тут тоже все понятно:

    [http://api.example.com/my-folder/my-doc](http://api.example.com/my-folder/my-doc) - хорошо

    [http://api.example.com/My-Folder/my-doc](http://api.example.com/My-Folder/my-doc) - плохо
*   В URL нельзя включать расширения файлов

    Это значит, что когда мы хотим получить какой-либо файл с сервера, то мы не указываем его расширение:

    [http://api.college.com/student/3248234/course/2005/fall](http://api.college.com/student/3248234/course/2005/fall) - хорошо

    [http://api.college.com/student/3248234/course/2005/fall.json](http://api.college.com/student/3248234/course/2005/fall.json) - плохо

## РАСПИСАТЬ ДАЛЬШЕ&#x20;















Источник: [https://habr.com/ru/companies/itq\_group/articles/705598/](https://habr.com/ru/companies/itq\_group/articles/705598/)

[https://habr.com/ru/articles/590679/](https://habr.com/ru/articles/590679/) (новая)
