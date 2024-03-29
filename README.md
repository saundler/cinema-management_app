# Инструкция по использованию приложения кинотеатра

## Введение
Это руководство содержит инструкции по использованию приложения кинотеатра, предназначенного для управления сеансами, билетами и местами в кинотеатре. Оно охватывает основные функции, такие как добавление фильмов и сеансов, покупка и возврат билетов, а также просмотр доступных мест.

## Запуск приложения
Для работы с приложением убедитесь, что на вашем компьютере установлена Java. Запустите приложение через среду разработки или используйте командную строку для компиляции и запуска Java-файлов.

## Основные команды

### 1. Добавление фильма (`add movie`)
- Введите команду `add movie`.
- Следуйте инструкциям для ввода названия фильма и его длительности.
- Фильм будет добавлен в список доступных фильмов.

### 2. Добавление сеанса (`add session`)
- Введите команду `add session`.
- Выберите фильм из списка и укажите время начала сеанса.
- Сеанс будет добавлен в расписание кинотеатра.

### 3. Удаление сеанса (`delete session`)
- Введите команду `delete session`.
- Следуйте инструкциям для выбора и удаления существующего сеанса.

### 4. Удаление фильма (`delete movie`)
- Введите команду `delete movie`.
- Следуйте инструкциям для выбора и удаления существующего фильма вместе со всеми его сеансами.

### 5. Покупка билета (`buy ticket`)
- Введите команду `buy ticket`.
- Выберите сеанс и место.
- Следуйте инструкциям для завершения покупки билета.

### 6. Возврат билета (`return ticket`)
- Введите команду `return ticket`.
- Выберите билет для возврата.
- Следуйте инструкциям для завершения процесса возврата билета.

### 7. Просмотр доступных мест (`view places`)
- Введите команду `view places`.
- Выберите сеанс, чтобы просмотреть информацию о занятых и свободных местах.

### 8. Завершение работы (`exit`)
- Введите команду `exit` для выхода из приложения.

## Важные замечания
- Убедитесь, что вводите информацию строго по инструкциям приложения.
- В случае ошибок или некорректного ввода приложение предоставит соответствующие подсказки для исправления.

## Заключение
Следуйте этим инструкциям для эффективного управления кинотеатром. Это приложение поможет организовать работу кинотеатра, управлять расписанием сеансов, и обеспечивать удобное бронирование и возврат билетов.

## Структура проекта
Приложение состоит из следующих основных компонентов:
- **Main.java**: Главный класс, содержащий точку входа в приложение и меню пользователя.
- **Cinema.java**: Класс, отвечающий за управление данными кинотеатра, включая фильмы, сеансы и билеты.
- **User.java**: Класс, представляющий пользователя и его возможности покупки и возврата билетов.
- **Movie.java**: Класс, содержащий информацию о фильме.
- **Session.java**: Класс, описывающий сеанс в кинотеатре, включая время начала и конца, а также статусы мест.
- **Ticket.java**: Класс, представляющий билет, связанный с конкретным сеансом и местом.
- **JsonUtil.java**: Класс, предоставляющий методы для сохранения и загрузки данных в формате JSON.
