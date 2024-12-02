# Тестовое задание

## API
Реализовано API для регистрации, авторизации:

Для обработки запросов был создан <a href="https://github.com/M1estere/laravel-test/blob/main/app/Http/Controllers/AuthController.php">AuthController</a>, где в каждом методе обрабатываются разные случаи и в зависимости от ситуации возвращаются разные значения\
Для всех методов были добавлены проверки исключений, возвращаются разные статус коды, был написал swagger\

Пример запроса на регистрацию пользователя "user3@example.com"
![reg](https://github.com/user-attachments/assets/d583390e-0b70-463b-93ac-c1953c5f6249)

Пример запроса на авторизацию того же пользователя
![log](https://github.com/user-attachments/assets/372090a0-13fa-4e4b-8161-58ac8cfb649c)

Пример запроса на получение данных текущего авторизованного пользователя
![profile](https://github.com/user-attachments/assets/edbdf64f-47f8-4847-ba50-ab62b05c55df)
