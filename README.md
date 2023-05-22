# SkillFactory-Module-F4-Homework
Клонируем проект на ПК при помощи git clone https://github.com/ConstantinKapanevs/SkillFactory-Module-F4-Homework.git

Открываем BackEnd директорию в IDE (рекомендуется при помощи PyCharm).
В открывшемся диалоговом окне выбираем директорию для виртуальной среды, интерпретатор, и файл с зависимостями (Предложенные по умолчанию).
Активируем виртуальное окружение (venv\scripts\activate), если оно не активировалось автоматически.
Или вручную выбираем интерпретатор (file-> settings -> Project: BackEnd -> Python Interpreter) ,
создаем виртуальное окружение (python -m venv venv) и активируем его (venv\scripts\activate).
В каталоге BackEnd создаем файл .env и прописываем в нем SEKRET_KEY = Сгенерированный ключ
Ключ для Django можно сгенерировать https://djecrety.ir/
Запускаем сервер из каталога project (python manage.py runserver)
Доступ к DRF API Root http://127.0.0.1:8000/api/v1/
Доступ к документации к API http://127.0.0.1:8000/doc/ или http://127.0.0.1:8000/swagger/

Открываем FrontEnd директорию в IDE (рекомендуется при помощи VSCode).
В терминале устанавливаем зависимости (npm i)
Запускаем наш проект (npm start)
