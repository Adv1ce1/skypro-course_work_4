Job Search App
Проект "Job Search App" представляет собой приложение для поиска и обработки вакансий из различных API. Пользователь может выполнять поиск вакансий, отображать результаты, сохранять вакансии в файлы.

Установка
Для установки проекта вам потребуется выполнить следующие шаги:

Склонируйте репозиторий с помощью команды:
   git clone https://github.com/AndreyAgeew/skypro-course_work_4.git
Перейдите в папку проекта:
    cd skypro-course_work_4
Установите необходимые зависимости, выполнив команду (для работы приложения требуется python >= 3.11):
    pip install -r requirements.txt
Использование
Для запуска приложения выполните следующую команду:

    python main.py
После запуска приложения вы увидите меню с доступными действиями:

Поиск вакансий: Выполняет поиск вакансий по заданной должности.
Отобразить вакансии: Отображает найденные вакансии.
Сохранить вакансии в файл: Сохраняет найденные вакансии в файлы JSON и CSV.
Выход: Завершает работу приложения.
Функциональность
Класс JobSearchApp
Класс JobSearchApp представляет основное приложение для выполнения операций по поиску и обработке вакансий.

Методы класса
__init__(self): Инициализирует объект JobSearchApp.
_interact_with_user(self): Обеспечивает взаимодействие с пользователем и обработку его выбора.
__search_vacancies(self): Выполняет поиск вакансий.
__get_title(vacancy): Получает название вакансии.
__get_link(vacancy): Получает ссылку на вакансию.
__get_salary(vacancy): Получает зарплату от вакансии.
__get_date_published(vacancy): Получает дату публикации вакансии.
__get_currency(vacancy): Получает валюту вакансии.
__check_currency(title, link, salary, date, currency): Проверяет валюту и преобразует зарплату.
__display_vacancies(self): Отображает найденные вакансии.
__filtered_vacancies(self): Фильтрует вакансии по названию профессии.
__sorted_vacancy_for_salary(self): Сортирует вакансии по окладу.
__sorted_vacancy_for_date(self): Сортирует вакансии по дате публикации.
__save_vacancies_to_files(self): Сохраняет вакансии в файлы JSON и CSV.
