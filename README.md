# Обрезка ссылок с помощью VK

## Описание
Скрипт получает на вход ссылку, сокращает её и указывает количество кликов по ней
## Требования
Для работы требуется библиотека requests 2.32.4 и python-decouple 3.8
```
pip install requirements.txt
```
## Настройка
Для запуска скрипта требуется файл `.env` с переменной окружения `TOKEN` содержащей ваш ключ доступа к api VK. Для кастомизации достаточно отредактировать переменную `token` в функции `main`.

## Использование
При запуске скрипта требуется указать ссылку 
```
python main.py https://www.google.com/
```
<img width="456" height="44" alt="image" src="https://github.com/user-attachments/assets/6096b887-dd44-4a3e-96ad-1165b617433d" />


Если ссылка уже сокращена скрипт выдаст количество кликов по ней.
```
python main.py https://vk.cc/snBwO
```
<img width="415" height="40" alt="image" src="https://github.com/user-attachments/assets/ca8c4d2e-2a48-4a4e-a7c9-36f7f47e7ed5" />




