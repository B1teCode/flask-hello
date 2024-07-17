# Flask App "Hello Recruto"

This is a simple Flask application that returns a personalized greeting message based on query parameters.

## Prerequisites

- Python 3.x
- Flask

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/B1teCode/flask-hello.git
   cd flask-hello
   ```

2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```sh
   pip install Flask
   ```

## Running the Application

1. Run the Flask app:
   ```sh
   python main.py
   ```

2. Open your web browser and go to `http://localhost:80`. You should see the default greeting message.

3. To customize the greeting, add `name` and `message` parameters to the URL, like this:
   ```
   http://localhost:80/?name=John&message=How%20are%20you

## Files

- `main.py`: The main application file.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# Flask приложение "Hello Recruto"

Это простое Flask приложение, которое возвращает персонализированное приветственное сообщение на основе параметров запроса.

## Предварительные требования

- Python 3.x
- Flask

## Установка

1. Клонируйте репозиторий:
   ```sh
   git clone https://github.com/B1teCode/flask-hello.git
   cd flask-hello
   ```

2. Создайте и активируйте виртуальное окружение:
   ```sh
   python -m venv venv
   source venv/bin/activate  # В Windows используйте `venv\Scripts\activate`
   ```

3. Установите необходимые пакеты:
   ```sh
   pip install Flask
   ```

## Запуск приложения

1. Запустите Flask приложение:
   ```sh
   python main.py
   ```

2. Откройте ваш веб-браузер и перейдите по адресу `http://localhost:80`. Вы должны увидеть приветственное сообщение по умолчанию.

3. Для кастомизации приветствия добавьте параметры `name` и `message` в URL, например:
   ```
   http://localhost:80/?name=Иван&message=Как%20дела
   ```

## Файлы

- `main.py`: Основной файл приложения.

## Вклад

Будем рады вашим предложениям! Пожалуйста, сделайте fork репозитория и создайте pull request.

## Лицензия

Этот проект лицензирован по лицензии MIT - смотрите файл [LICENSE](LICENSE) для подробностей.
