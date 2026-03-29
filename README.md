# Student Management System

Простое Spring Boot приложение для управления студентами с REST API.

Name: Fanisova Raniia

Group: COMFCI-24

## Технологии

- Java 21
- Spring Boot 4.0.5
- Spring Web
- Maven

## Структура проекта
student-management/

├── src/main/java/com/example/studentmanagement/

│   ├── StudentManagementApplication.java    # Главный класс

│   ├── Student.java                         # Модель (Entity)

│   └── StudentController.java               # REST Controller

└── pom.xml                                  # Зависимости Maven

## Как запустить

1. Открыть проект в IntelliJ IDEA
2. Настроить JDK (Java 21)
3. Запустить `StudentManagementApplication.java`
4. Приложение будет доступно на `http://localhost:8080`

## REST API Endpoints

| Метод | URL | Описание |
|-------|-----|----------|
| GET | `/api/students` | Получить всех студентов |
| GET | `/api/students/{id}` | Получить студента по ID |
| POST | `/api/students` | Создать нового студента |
| PUT | `/api/students/{id}` | Обновить студента |
| DELETE | `/api/students/{id}` | Удалить студента |
