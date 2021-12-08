# Проект CatBot

CatBot - это бот для Telegram, который присылает пользователю котиков.

## Установка

1. Клонируйте репозиторий с github
2. Создайте виртуальное окружение
3. Установите зависимости `pip install -r requirements.txt`
4. Создайте файл `settimgs.py` и создайте в нём переменные
    ```
    API_KEY = "Ключ вашего бота"
    PROXY_URL = "URL socks5-прокси"
    PROXY_USERNAME = "Username для авторизации на прокси"
    PROXY_PASSWORD = "Пароль  для авторизации на прокси"
    USER_EMOJI = [':smiley_cat:', ':smiling_imp:', ':panda_face:', ':dog:']
    ```
5. Запустите бот командой `python mybot.py `