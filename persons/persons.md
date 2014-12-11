Персоны
=======

Получение списка всех персон.
-----------------------------
Уровень доступа — **public**

```
GET https://api.i-news.kz/person/get-all?appId=***&appKey=***
```

```
[
    {"id" : "1", "title" : "Нурсултан Назарбаев"},
    …
]
```

Получение нескольких персон по списку id.
-----------------------------------------
Уровень доступа — **public**

```
GET https://api.i-news.kz/person/get-many?ids[0]1=&ids[1]=3&appId=***&appKey=***
```

```
[
    {"id" : "1", "title" : "Нурсултан Назарбаев", "description" : "Президент Республики Казахстан", "photo" : "/images/persons/nazarbayev.jpg"},
    {"id" : "3", "title" : "Владимир Путин", "description" : "Президент Российской Федерации", "photo" : "/images/persons/putin.jpg"},
]
```

Получение одной персоны по id.
-----------------------------
Уровень доступа — **public**

```
GET https://api.i-news.kz/person/get-one?id=1&appId=***&appKey=***
```

```
{"id" : "1", "title" : "Нурсултан Назарбаев", "description" : "Президент Республики Казахстан", "photo" : "/images/persons/nazarbayev.jpg"}
```