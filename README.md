# Правильный деплой frontend-приложения на heroku
Small example about deploying to Heroku
Инструкция по деплою приложения:
0. Скачать данный репозиторий и использовать его как шаблон

1. Зарегистрироваться на heroku.com
2. Установить Heroku Toolbelt (https://devcenter.heroku.com/articles/getting-started-with-nodejs#set-up)
3. Перейти в папку с проектом из данного репозитория и запустить командную строку/терминал
4. Авторизоваться в heroku `heroku login`
5. Создать новое приложение `heroku create name`, где name - уникальное имя приложения, для которого будет создан домен и репозиторий
6. Загрузить код приложения на удалённый git-репозиторий 'git push heroku master'
7. Запустить worker с помощью команды 'heroku ps:scale web=1'
8. Посмотреть своё приложение по адресу name.herokuapp.com, где name - имя вашего приложения