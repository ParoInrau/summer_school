# Рефакторинг раздела Getting started в справочнике API на сайте Xsolla

__Описание проекта__.

*Предполагается сделать:*

- прочитать текст
- отредактировать
* сохранить

- конец.

| Классная таблица | Очень классная |
| ------------- | ------------- |
| 1  | 3  |
| 2  | 4  |


  
1. Item A
2. Item B
3. Item C

# Справочник API

## GetProductsList_ID

Данный API позволяет пользователю получить список подключенных продуктов по ID проекта.


- Параметры запроса:

`project_id integer ID проекта`


- Параметры ответа:

`project_id : status`


### Примеры

- Пример HTTP-запроса:

` GET https://api.example.com/products/{project_id} `

`Headers: `

`Authorization: Basic <your_authorization_basic_key> `

- Пример HTTP-ответа:

`{`

`Product1:connected, `

`Product2:disconnected`

`}`
