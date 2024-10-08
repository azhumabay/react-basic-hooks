# TODO Application

Это приложение TODO позволяет пользователям добавлять, удалять и отмечать задачи как выполненные. В проекте используются React Hooks: `useReducer` для управления состоянием и `useContext` для управления глобальным состоянием. Также реализована фильтрация задач с помощью `useMemo` и синхронизация с `localStorage` для сохранения списка задач между сессиями.

## Основные функции

- **Добавление задачи:** Пользователь может добавить новую задачу через форму.
- **Удаление задачи:** Пользователь может удалить любую задачу из списка.
- **Отметка задачи как выполненной:** Пользователь может отмечать задачи как выполненные.
- **Фильтрация задач:** Возможность фильтровать задачи по состоянию (все, выполненные, невыполненные).
- **Синхронизация с localStorage:** Задачи сохраняются в `localStorage`, чтобы не теряться между сессиями.

## Структура приложения

- **App:** Основной компонент приложения.
- **TodoProvider:** Провайдер контекста для управления состоянием TODO.
- **TodoList:** Компонент, отображающий список задач.
- **TodoItem:** Компонент для отображения одиночной задачи.
- **TodoForm:** Форма для добавления новой задачи.
- **TodoFilter:** Компонент для фильтрации задач.
- **todoReducer:** Файл, содержащий логику редюсера для управления состоянием задач.

## Интерфейс

- Поле ввода для добавления новой задачи.
- Кнопка для добавления задачи.
- Список задач с возможностью их удаления и изменения статуса.
- Фильтры для переключения между различными типами задач.
- Дизайн выполнен с использованием Material UI.

## Сущность TODO

- **id:** `number` (идентификационный номер задачи, уникальный).
- **title:** `string` (название задачи).
- **status:** `boolean` (состояние задачи: выполнено или нет).

## Деплой

Приложение развернуто на https://react-basic-hooks-ecru.vercel.app/
