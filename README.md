# Teplyakov-Roman-Track-Web-development
Проект на конкурс Искусство кода. Трек: Веб-разработка. Автор: Тепляков Роман Иванович.

*денег на то, чтобы захостить сайт нет))) Но его можно легко запустить со компьютера.

# Структура репозитория
* `README.md` -- документация к репозиторию и инструкция для запуска
* `kurskayabitva` -- папка с программой в которой нужно будет вводить команды для запуска
* `requirements.txt` -- файл с требующимися модулями
* `kurskayabitva.zip` -- архив с проектом (содержит те же файлы и 
  документацию, что и папка kurskayabitva и readme.md)
* ну и соответственно презентация, видео-демонстрация и фото сайта.


# Запуск проекта

Для начала необходимо установить необходимую библиотеку (также обязательно 
на компьютере должен быть установлен интерпретатор языка Python, желательно 
версии от 3.8 и выше. [интерпретатор Python](https://www.python.org/downloads/))

Чтобы установить необходимый модуль Django, запустите следующую команду в командной строке:

`pip install -r path_to_project_dir/requirements.txt`

вместо "path_to_project_dir" должен быть прописан путь до папки с файлами из репозитория на вашем устройстве. (в видеодемонстрации я упоминаю об этом).

Далее, через командную строку, в папке `kurskayabitva` запускаем команду:
`python manage.py runserver`
после чего в окне командной строки вам выведется адрес локального хоста, который мы вводим в браузер и переходим на сайт.
(пример адреса: `/127.0.0.1:8000/`)

Запуск также продемонстрирован в видеоролике.
