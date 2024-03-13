### Тестовое задание на позицию JS Frontend/Fullstack Developer

#### Закончив реализацию, открывайте Pull Request в этот репозиторий

Здесь рабочее базовое приложение, в которое предлагается нарастить функциональность.
Приложение во многом похоже на то, с чем вам предстоит работать в QIWI.

Оно работает в связке с бэкендом - тестовым заданием https://github.com/qiwi/test_task_node_server
, размещенным по адресу https://test-task.qiwi.tools:2211/api/

Бэкенд также можно поднять локально при желании и выполнить тестовое задание fullstack. Это будет бонусом кандидату.

В текущей реализации приложение-boilerplate содержит страницу авторизации и маршрутизацию на страницу, где нужно реализовать список пользователей.

Данные для авторизации:
```
email: candidate@e.ru
password: candidate
```

#### Для выполнения задания нужно добавить вывод списка пользователей в авторизованной зоне.
Для этого их необходимо будет получить с сервера.

Рекомендуется пользоваться [API-документацей](https://qiwi.github.io/test_task_node_server/)

Полученный при авторизации JWT-токен потребуется для доступа к [запросам авторизованной зоны](https://qiwi.github.io/test_task_node_server/#api-User)

JWT-токен необходимо указать в заголовке Authorization после ключевого слова Bearer.

#### Для запуска приложения достаточно выполнить:
*при условии установленной среды Node.js >= 8.11

```
npm start
```