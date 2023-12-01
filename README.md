## Описание
REST API платформы личных блогов.
Аутентифицированный пользователь авторизован на изменение и удаление своего контента,
в остальных случаях доступ предоставляется только для чтения.

- Получение JWT-токена.
- Чтение/Публикация/Редакция/Удаление записей и комментариев.
- Подписка на пользователей.


## Инструкция по запуску проекта
1. Склонируйте проект себе на компьютер.
2. Создайте  virtual environment для папки с проектом: 

   - Linux/macOS
    
    ```bash
    python3 -m venv venv
    ```
    
- Windows
    
    ```python
    python -m venv venv
    ```

3. Активируйте виртуального окружения

- Linux/macOS
    
    ```bash
    source venv/bin/activate
    ```
    
- Windows
    
    ```bash
    source venv/Scripts/activate
    ```
4. Все дальнейшие команды в терминале надо выполнять с активированным виртуальным окружением.

Обновите pip:

```bash
python -m pip install --upgrade pip
```

5. Установите зависимостей из файла *requirements.txt*:
команда в терминале **pip install -r requirements.txt** (Windows).

```bash
pip install -r requirements.txt
```

6. Применете миграцию

    
В директории с файлом manage.py выполните команду: 

```bash
python manage.py migrate
```
