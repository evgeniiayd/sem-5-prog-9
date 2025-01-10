# Лабораторная работа 9, Яблонская Евгения

1. Перед началом работы необходимо запустить команду ```python init_db.py```, чтобы была создана база данных с клиентами. Она имеет следующую структуру, представленную в файле models.py:

![image](https://github.com/user-attachments/assets/213cb434-ef7a-4443-ad73-d6321541cda6)

Для реализации была использована библиотека SQLAlchemy.

Запуск приложения.

![image](https://github.com/user-attachments/assets/dafdf1bf-b46f-4315-90a2-5512fb3d8f34)

Результат тестирования (код теста представлен в файле test_request, запрос был сделан с помощью библиотеки request), где последовательно происходят: 
- сначала POST-запрос, с введением логина и пароля, а также получения токена,
- после GET-запрос с помощью токена узнается уровень пользователя и количество потраченных денег.

![image](https://github.com/user-attachments/assets/6071800a-7334-4be0-a703-2e91fc3d8fe9)

Тесты:

![image](https://github.com/user-attachments/assets/fb7d2101-c342-4ed8-98f0-af8c03c94b22)


