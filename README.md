# Бот для VK Experts.
___
Бот, который автоматически оценивает записи в категории IT.
___
Режимы бота:

    Фарм (1) - бот проставляет на все записи рейтинг -1. (Средний рейтинг: 4.7-4.9)
    Умное оценивание (2) - бот анализирует запись и в следствии анализа ставит ей оценку (Средний рейтинг: 4.0-4.3)
    
___
Структура конфига:

    access_token: токен от страницы
    sleep_time: время для остановки, между оцениванием записи
    alt_categories: будет ли работать бот в альтернативных от IT категориях
___
Запуск бота:

    git clone https://github.com/k0tmurlik/vk-experts.git
    pip3 install -r requirements.txt
    python3 main.py
    
