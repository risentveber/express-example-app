## Пример простого приложения на epxress

В рамках вводной лекции по использованию express для создания API.

### Установка зависимостей

```bash
npm install
```

### Запуск приложения

При изменениях в коде перезапуск происходит автоматически благодаря [nodemon](https://nodemon.io/).

```bash
npm run start
```

Приложение запустится по адресу localhost:3000.

### Изучение работы приложения

Для того, чтобы поиграться с методами предоставляемыми простым API рекомендую
использовать консольные утилиты curl или [httpie](https://httpie.org/)

```bash
http GET localhost:3000/users/ # список пользователей
http POST localhost:3000/users/ name=Tim # создание пользователя
http GET localhost:3000/users/0 # просмотр пользователя
http PUT localhost:3000/users/0 name=Tom # обновление
http DELETE localhost:3000/users/0 # удаление
```


