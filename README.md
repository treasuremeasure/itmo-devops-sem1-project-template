# Финальный проект 1 семестра

REST API сервис для загрузки и выгрузки данных о ценах.

## Требования к системе

- **Операционная система**: Windows, Linux, macOS.
- **Go**: версия 1.20 и выше.
- **PostgreSQL**: версия 13 и выше.
- **Аппаратные требования**:
  - Минимум 1 ГБ оперативной памяти.
  - Свободное дисковое пространство: 200 МБ для базы данных.

## Установка и запуск

1. Убедитесь, что установлены Go и PostgreSQL.
2. Склонируйте репозиторий: git clone <repository_url> && cd <repository_directory>
3. Создайте базу данных и таблицу: psql -U validator -d postgres -c "CREATE DATABASE project-sem-1;"
4. Запустите скрипт prepare.sh для настройки базы данных: ./prepare.sh
5. Запустите сервер: ./run.sh
6. Сервер будет доступен по адресу:http://localhost:8080



## Тестирование

Пример директории sample_data — это разархивированная версия файла sample_data.zip.

Для тестирования используйте скрипт tests.sh:


./tests.sh

Этот скрипт выполняет два теста:

Тестирование POST-запроса с файлом sample_data.zip.
Тестирование GET-запроса и проверка загрузки файла data.zip.

## Контакт

К кому можно обращаться в случае вопросов
