# TODO manager

## Предварительные настройки

Перед запуском контейнеров docker'а необходимо из каталога todos/frontend выполнить команды. Сначала:

    yarn install

а затем:

    yarn build

## Запуск

Для запуска всех сервисов приложения необходимо из каталога todos выполнить:

    docker-compose up --build -d

После того, как все сервисы запустятся приложение будет досутпно в броузере по даресу localhost (localhost:80).

В данный момент в системе зарегистрированы 2 пользователя:

1. Алексей Кассь (login: "alexeykass", password: "alexeykass")

1. Иван Иванов (login: "i.i.ivanov", password: "ivanov")

Пользователь Алексей Кассь является руководителем по отношению к пользователю Иван Иванов.

## Остановка

Для остановки всех сервисов приложения необходимо из каталога todos выполнить:

    docker-compose down
