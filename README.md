# Бот для VK Experts.
___
Бот, который автоматически оценивает записи в категории IT.
___
Режимы бота:

    Фарм (1) - бот проставляет на все записи рейтинг -1.
    Умное оценивание (2) - бот анализирует запись и в следствии анализа ставит ей оценку.
   
___
<i>Инструкция по запуску на Ubuntu.</i>
___
Установка бота:
    
    git clone https://github.com/k0tmurlik/vk-experts.git
    cd vk-experts
    pip3 install -r requirements.txt
    
Редактируем конфиг:

    nano config.py
    Ctrl + X
    Y

Структура конфига:

    access_token: токен от страницы
    sleep_time: время для остановки, между оцениванием записи
    alt_categories: будет ли работать бот в альтернативных от IT категориях

    
Запускаем бота:

    python3 main.py
