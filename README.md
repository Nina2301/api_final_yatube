<div align="center">
  <h3 align="center">API для Yatube</h3>
  <p align="center">
    Проект «API для социальной сети Yatube»
    <br />
  </p>
</div>

## Описание

Данный проект предоставляет доступ к сервису Yatube посредством API. 

## Как запустить проект:

1. Клонировать репозиторий и перейти в него в командной строке:
   ```sh
   git clone https://github.com/Nina2301/api_final_yatube.git
   ```
   ```sh
   cd api_final_yatube
   ```

2. Cоздать и активировать виртуальное окружение:
   ```sh
   python3 -m venv env
   ```
   ```sh
   source env/bin/activate
   ```
   ```sh
   python3 -m pip install --upgrade pip
   ```

3. Установить зависимости из файла requirements.txt:
   ```sh
   pip install -r requirements.txt
   ```

4. Выполнить миграции:
   ```sh
   python3 manage.py migrate
   ```

5. Запустить проект:
   ```sh
   python3 manage.py runserver
   ```

## Авторы

Яндекс Практикум

Нина Карлова 60 когорта nina-karlova@yandex.ru
