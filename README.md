# Kittygram

Kittygram - это социальная сеть для обмена фотографиями любимых питомцев.\
Этот проект представляет собой полностью функциональное приложение, состоящее из бэкенд-части, разработанной на Django, и фронтенд-части на React.
***
## Инструкция по установке
#### Установка проекта на локальный компьютер
Следуйте этим шагам, чтобы установить и запустить Kittygram на вашем локальном компьютере:

Склонируйте репозиторий с GitHub:
>    git clone https://github.com/vhg860/infra_sprint1.git

Создайте и активируйте виртуальное окружение:
>    python3 -m venv venv\
>    source venv/bin/activate

Обновите pip и установите зависимости из файла requirements.txt:
>    python -m pip install --upgrade pip\
>    pip install -r requirements.txt

Применение миграций:
>    python manage.py migrate

Запуск проекта в dev-режиме:
>    python manage.py runserver
***
## Используемые библиотеки

Проект Kittygram использует следующие основные библиотеки и фреймворки:

- [Django](https://www.djangoproject.com/)
- [React](https://reactjs.org/)
- Другие библиотеки и зависимости указаны в файле requirements.txt
***
## Настройка переменных окружения (env)

Для корректной работы проекта Kittygram вам потребуется настроить переменные окружения.\
Создайте файл .env в корневой директории проекта и укажите необходимые переменные.\
Пример файла .env:
```html
DEBUG=True
SECRET_KEY=mysecretkey
ALLOWED_HOSTS = ['xxx.xxx.xxx.xxx', '127.0.0.1', 'localhost', 'ваш_домен']
```
 Вместо xxx.xxx.xxx.xxx укажите IP сервера, а вместо <ваш_домен> – доменное имя
### Автор
[Дмитрий](https://github.com/vhg860)
