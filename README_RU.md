# Сайт - мессенджер

<br>
<div style="text-align:center">
  <img src="./images_readme/main_page.png" width="1000"/>
  <img src="./images_readme/all_users.png" width="1000"/>
</div>
<br>

## Функционал сайта

Этот сайт представляет из себя простое приложение - чат для переписок.

На сайте можно переписываться с пользователями, также реализована регистрация и авторизация.

<br>
<div style="text-align:center">
  <img src="./images_readme/login.png" width="1000"/>
</div>
<br>

## Основные страницы сайта

- Главная страница по адресу `/main`
- Все пользователи по адресу `/main/users`
- Страница регистрации `/auth/sign_up`
- Страница входа `/auth/login`

## Технологии использованные при разработке сайта

#### Для frontend части были использованы следующие фреймворки и технологии
- HTML/CSS/JS
- Bootstrap

Сайт является адаптивным и доступен для комфортного просмотра на устройствах с разными размерами экранов.

#### Для backend части были использованы следующие фреймворки и технологии
- Node.js
- Express.js
- MongoDB

#### Общение между пользователями реализованно при помощи постоянного соединения (WebSocket)
- SocketIO


## Запуск приложения

Для того чтобы запустить приложение клонируйте репозиторий при помощи `git clone`. 

Далее вы должны создать базу данных mongoDB Для подключения к БД как и для формирования JWT используются переменные окружения, вы можете определить их в файле `.env` или задать эти параметры напрямую.

Для загрузки всех пакетов и модулей используйте команду `npm init`.

Запуск сервера происходит командой `npm start` или `npm dev` для запуска с пакетом `nodemon`.