# creationANewEmployee_UI_tests
Создание сотрудника. Шаги тест-кейса.

Шаги

1
ШАГ
Выбрать Организацию ПАО Сбербанк
ТЕСТОВЫЕ ДАННЫЕ
Нажмите, чтобы ввести данные теста
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
Отображаются сотрудники, входящие в эту Организацию
Кнопка Добавить сотрудника активна

2
ШАГ
Выбрать  Территориальное отделение Байкальский банк
ТЕСТОВЫЕ ДАННЫЕ
Нажмите, чтобы ввести данные теста
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
Отображаются сотрудники, входящие в это Территориальное отделение
Кнопка Добавить сотрудника активна

3
ШАГ
Выбрать Головное отделение Бурятское отделение №8601
ТЕСТОВЫЕ ДАННЫЕ
Нажмите, чтобы ввести данные теста
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
Отображаются сотрудники, входящие в это Головное отделение
Кнопка Добавить сотрудника активна

4
ШАГ
Нажать Добавить сотрудника
ТЕСТОВЫЕ ДАННЫЕ
Нажмите, чтобы ввести данные теста
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
Откроется форма создания сотрудника
Кнопка Сохранить не активна

5
ШАГ
Ввести Должность
ТЕСТОВЫЕ ДАННЫЕ
Нажмите, чтобы ввести данные теста
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
Нажмите, чтобы ввести ожидаемый результат

6
ШАГ
Выбрать Роль из списка
ТЕСТОВЫЕ ДАННЫЕ
Нажмите, чтобы ввести данные теста
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
Роли упорядочены по алфавиту

7
ШАГ
Ввести табельный номер
ТЕСТОВЫЕ ДАННЫЕ
формат цифры без букв, номер индивидуальный, формат 01234567
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
Нажмите, чтобы ввести ожидаемый результат

8
ШАГ
Нажать Связать
ТЕСТОВЫЕ ДАННЫЕ
Нажмите, чтобы ввести данные теста
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
Если имеется учетная запись пользователя с тем же табельным номером, запись пользователя связывается с табельным номером
Информ сообщение об удачном связывании по табельному номеру
если нет - сообщение WARNING вида: отсутствует учетная запись с указанным табельным номером.

9
ШАГ
Ввести Фамилию, Имя и при наличии Отчество
ТЕСТОВЫЕ ДАННЫЕ
Поле отчество не является обязательным
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
После заполнения Фамилии и имени активна кнопка Сохранить

10
ШАГ
Ввести начало периода действия сотрудника
ТЕСТОВЫЕ ДАННЫЕ
Дата начала периода действия не может быть позже даты окончания периода действия сотрудника
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
Нажмите, чтобы ввести ожидаемый результат

11
ШАГ
Ввести окончание периода действия сотрудника
ТЕСТОВЫЕ ДАННЫЕ
Дата начала периода действия не может быть позже даты окончания периода действия сотрудника
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
Нажмите, чтобы ввести ожидаемый результат
Up

12
УдалитьВложить файлыКлонироватьДобавить общий шагДобавить шаг
ШАГ
Нажать "Сохранить"
ТЕСТОВЫЕ ДАННЫЕ
Нажмите, чтобы ввести данные теста
ОЖИДАЕМЫЙ РЕЗУЛЬТАТ
Форма создания сотрудника исчезла 
Сотрудник добавлен в список своего подразделения
Сообщение об успешном создании сотрудника
Сотрудника видно в списке своего подразделения, если установлен чекбокс "Только действующие" и текущая дата входит в период даты начала действия и даты окончания действия сотрудника. В противном случае сотрудника видно без установленного чекбокса "Только действующие"