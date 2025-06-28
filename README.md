# Weather application

![big_screen.png](static/icon/big_screen.png)

Цей проект розроблено з метою ознайомлення із роботою API, принципом отримання даних від віддаленого серверу, вмінням їх обробляти, структурувати та застосовувати у своємо проєкті. А саме застосовувалось API такого веб-ресурсу як [OpenWeatherMap](https://openweathermap.org). Проєкт допоможе розібратися із роботою файлів JSON, як правильно отримувати та зберігати дані у файлах з типом .json. Та познайомити користувача з інтерфейсом застосунку розробленим за допомогою пакету [CustomTkinter](https://customtkinter.tomschimansky.com)

### Зміст репозиторія:

1. [Основні модулі проєкту](#all-modules)
2. [Розгортання проєкту](#download-project)
3. [Створення віртуального оточення проєкту](#create-venv)
4. [Завантаження модулів до віртуального оточення](#download-modules-venv)
5. [Старт проєкту](#start-project)
6. [Основні механіки проєкту](#all-mechanics)
7. [Висновок по проєкту](#result) 
___
<h4 id= 'all-modules'>Основні модулі проєкту:</h4>
All modules

- [customtkinter](https://customtkinter.tomschimansky.com/)
- [json](https://docs.python.org/3/library/json.html)
- [requests](https://pypi.org/project/requests/)
- [pillow](https://pypi.org/project/pillow/)
- [os](https://docs.python.org/uk/3.13/library/os.html)
- [colorama](https://pypi.org/project/colorama/)
- [datetime](https://docs.python.org/3/library/datetime.html)
___
<h4 id= 'download-project'>Розгортання проєкту:</h4>
Download project

1. Склонувати з Git Hub репозиторію
git clone (посилання з github) - ця команда клонує репозиторій за допомогую посилання, після цього треба його відкрити в explorer

2. Завантажити за допомогою zip-архіву
<>Code -> local -> downoload ZIP - після цих дій, треба розпакувати ZIP архів в потрібній вам дерикторій на вашому комп'ютері
___
<h4 id= 'create-venv'>Створення віртуального оточення проєкту:</h4>
Сreate venv

1. Windows
python3 -m venv venv -> venv\Scripts\activate.bat  -  активізувати та встановити venv на віндовс

3. Mac OS або Linux
python3 -m venv venv -> source venv/bin/activate  - активізувати та встановити venv на лінукс або мак ос
___
<h4 id= 'download-modules-venv'>Завантаження модулів до віртуального оточення:</h4>
Download modules venv

1. Окремими модулями
pip install <назва_модуля> - встановлює модулі венв за допомогою інших модулей
3. За допомогою файлу requirements.txt
pip freeze -r requirements.txt - встановлює модулі венв за допомогою requirements.txt
___
<h4 id= 'start-project'>Старт проєкту:</h4>
Start project

python main.py - ця команда знаходиться в main.py і вона стартує наш проєкт, якщо цієї команди не буде, код не запуститься і працювати не буде.

<h4 id= 'result'>Висновок проєкту:</h4>
Result

Цей код дуже цікавий, він був створений для того щоб дивитися погоду зараз або в найближчий час в якомусь конктретному місті. Деякі люди яким дуже цікаво можуть подивитись
як він був зроблений та зробити такий самий, та зрозуміти що вони також так можуть. Для нього є свій додаток там де люди можуть подивитись погоду. Цей код написав перший курс
компанії WORLDIT. Для цього додатку було зроблено дизайн, додані смайлики, кнопки та система яка автоматично бере погоду з сайту. Для цього був підключений API ключ.
